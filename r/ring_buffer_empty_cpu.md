# Function: <code>ring_buffer_empty_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811480f0)
Location: kernel/trace/ring_buffer.c:4301
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811480f0-ffffffff81148172: ring_buffer_empty_cpu.part.41 (STB_LOCAL)
ffffffff81148180-ffffffff8114819e: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811530f8)
Location: kernel/trace/ring_buffer.c:4296
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811505f0-ffffffff81150670: ring_buffer_empty_cpu.part.41 (STB_LOCAL)
ffffffff81150670-ffffffff8115068a: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d0e9)
Location: kernel/trace/ring_buffer.c:4265
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8115b750-ffffffff8115b7d0: ring_buffer_empty_cpu.part.35 (STB_LOCAL)
ffffffff8115b7d0-ffffffff8115b7ed: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811600f9)
Location: kernel/trace/ring_buffer.c:4279
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8115ee00-ffffffff8115ee8c: ring_buffer_empty_cpu.part.39 (STB_LOCAL)
ffffffff8115ee90-ffffffff8115eead: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116d1be)
Location: kernel/trace/ring_buffer.c:4271
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8116b6e0-ffffffff8116b76c: ring_buffer_empty_cpu.part.39 (STB_LOCAL)
ffffffff8116b770-ffffffff8116b78e: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c1bf)
Location: kernel/trace/ring_buffer.c:4433
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8117ab50-ffffffff8117abdc: ring_buffer_empty_cpu.part.41 (STB_LOCAL)
ffffffff8117abe0-ffffffff8117abfe: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811899bf)
Location: kernel/trace/ring_buffer.c:4502
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81187910-ffffffff8118799c: ring_buffer_empty_cpu.part.42 (STB_LOCAL)
ffffffff811879a0-ffffffff811879be: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195110)
Location: kernel/trace/ring_buffer.c:4480
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81195110-ffffffff811951b6: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0bd0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811a0bd0-ffffffff811a0c76: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b953a)
Location: kernel/trace/ring_buffer.c:4572
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b71e0-ffffffff811b726c: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff811b7270-ffffffff811b7291: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6f7a)
Location: kernel/trace/ring_buffer.c:5182
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b4da0-ffffffff811b4e2c: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff811b4e30-ffffffff811b4e51: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7a0a)
Location: kernel/trace/ring_buffer.c:5291
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811b6810-ffffffff811b68a8: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff811b68b0-ffffffff811b68d1: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1c3a)
Location: kernel/trace/ring_buffer.c:5296
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811e0a00-ffffffff811e0a98: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff811e0aa0-ffffffff811e0ac1: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81218964)
Location: kernel/trace/ring_buffer.c:5338
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff812138c0-ffffffff81213950: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff81213950-ffffffff81213985: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812627da)
Location: kernel/trace/ring_buffer.c:5445
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8125d130-ffffffff8125d1c4: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff8125d1e0-ffffffff8125d215: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812797ba)
Location: kernel/trace/ring_buffer.c:5468
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff812743b0-ffffffff81274444: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff81274460-ffffffff81274495: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81294321)
Location: kernel/trace/ring_buffer.c:5385
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:rb_watermark_hit
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:rb_watermark_hit
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8128ea20-ffffffff8128eab4: ring_buffer_empty_cpu.part.0.isra.0 (STB_LOCAL)
ffffffff8128ead0-ffffffff8128eb05: ring_buffer_empty_cpu (STB_GLOBAL)
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
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021a2f0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffff80001021a2f0-ffff80001021a454: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045708c)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
c045708c-c0457160: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029ab80)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
c00000000029ab80-c00000000029ace0: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000178e94)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffe000178e94-ffffffe000178f72: ring_buffer_empty_cpu (STB_GLOBAL)
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
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811991f0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811991f0-ffffffff81199296: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a8d0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff8118a8d0-ffffffff8118a960: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196fc0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff81196fc0-ffffffff81197066: ring_buffer_empty_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ring_buffer_empty_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4bd0)
Location: kernel/trace/ring_buffer.c:4481
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:__find_next_entry
```
**Symbols:**

```
ffffffff811a4bd0-ffffffff811a4c7c: ring_buffer_empty_cpu (STB_GLOBAL)
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
