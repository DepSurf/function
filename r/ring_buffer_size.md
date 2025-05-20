# Function: <code>ring_buffer_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147050)
Location: kernel/trace/ring_buffer.c:4159
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81147050-ffffffff81147081: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f870)
Location: kernel/trace/ring_buffer.c:4154
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8114f870-ffffffff8114f8a0: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159aa0)
Location: kernel/trace/ring_buffer.c:4123
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81159aa0-ffffffff81159ad3: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c9e0)
Location: kernel/trace/ring_buffer.c:4137
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8115c9e0-ffffffff8115ca13: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169980)
Location: kernel/trace/ring_buffer.c:4129
Inline: True
```
**Symbols:**

```
ffffffff81169980-ffffffff811699b3: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811788d0)
Location: kernel/trace/ring_buffer.c:4291
Inline: True
```
**Symbols:**

```
ffffffff811788d0-ffffffff81178903: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185d90)
Location: kernel/trace/ring_buffer.c:4356
Inline: True
```
**Symbols:**

```
ffffffff81185d90-ffffffff81185dc3: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811930c0)
Location: kernel/trace/ring_buffer.c:4334
Inline: True
```
**Symbols:**

```
ffffffff811930c0-ffffffff811930ef: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119efa0)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffff8119efa0-ffffffff8119efcf: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5970)
Location: kernel/trace/ring_buffer.c:4426
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b5970-ffffffff811b599f: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3250)
Location: kernel/trace/ring_buffer.c:4972
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b3250-ffffffff811b327f: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3550)
Location: kernel/trace/ring_buffer.c:5079
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b3550-ffffffff811b357f: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dd310)
Location: kernel/trace/ring_buffer.c:5079
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811dd310-ffffffff811dd33f: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213a20)
Location: kernel/trace/ring_buffer.c:5121
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81213a20-ffffffff81213a59: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125d2d0)
Location: kernel/trace/ring_buffer.c:5227
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8125d2d0-ffffffff8125d309: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81274550)
Location: kernel/trace/ring_buffer.c:5234
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81274550-ffffffff81274589: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128ebc0)
Location: kernel/trace/ring_buffer.c:5142
Inline: True
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8128ebc0-ffffffff8128ebf2: ring_buffer_size (STB_GLOBAL)
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
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217548)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffff800010217548-ffff800010217590: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456f88)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
c0456f88-c0456fd4: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029a5e0)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
c00000000029a5e0-c00000000029a638: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001775b2)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffe0001775b2-ffffffe0001775f8: ring_buffer_size (STB_GLOBAL)
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
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811975c0)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffff811975c0-ffffffff811975ef: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a8a0)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffff8118a8a0-ffffffff8118a8cf: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195390)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffff81195390-ffffffff811953bf: ring_buffer_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_size(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2fa0)
Location: kernel/trace/ring_buffer.c:4335
Inline: True
```
**Symbols:**

```
ffffffff811a2fa0-ffffffff811a2fcf: ring_buffer_size (STB_GLOBAL)
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
