# Function: <code>ring_buffer_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148020)
Location: kernel/trace/ring_buffer.c:4271
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
**Symbols:**

```
ffffffff81148020-ffffffff811480e9: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114ff60)
Location: kernel/trace/ring_buffer.c:4266
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8114ff60-ffffffff81150038: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115b0a0)
Location: kernel/trace/ring_buffer.c:4235
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8115b0a0-ffffffff8115b165: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115e640)
Location: kernel/trace/ring_buffer.c:4249
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8115e640-ffffffff8115e717: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116b590)
Location: kernel/trace/ring_buffer.c:4241
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8116b590-ffffffff8116b661: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117aa80)
Location: kernel/trace/ring_buffer.c:4403
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8117aa80-ffffffff8117ab4d: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81186f80)
Location: kernel/trace/ring_buffer.c:4472
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81186f80-ffffffff81187042: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194a50)
Location: kernel/trace/ring_buffer.c:4450
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81194a50-ffffffff81194b18: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0510)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811a0510-ffffffff811a05d8: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b57e0)
Location: kernel/trace/ring_buffer.c:4542
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b57e0-ffffffff811b58a8: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b30c0)
Location: kernel/trace/ring_buffer.c:5152
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b30c0-ffffffff811b3188: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5780)
Location: kernel/trace/ring_buffer.c:5261
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b5780-ffffffff811b5862: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dfe10)
Location: kernel/trace/ring_buffer.c:5266
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811dfe10-ffffffff811dfef2: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213ca0)
Location: kernel/trace/ring_buffer.c:5308
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81213ca0-ffffffff81213d72: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e1c0)
Location: kernel/trace/ring_buffer.c:5415
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8125e1c0-ffffffff8125e29c: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81275210)
Location: kernel/trace/ring_buffer.c:5438
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81275210-ffffffff812752ec: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ring_buffer_empty(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128f5e0)
Location: kernel/trace/ring_buffer.c:5355
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:rb_watermark_hit
```
**Symbols:**

```
ffffffff8128f5e0-ffffffff8128f6bc: ring_buffer_empty (STB_GLOBAL)
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
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010218380)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffff800010218380-ffff80001021852c: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045826c)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
c045826c-c0458350: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029b170)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
c00000000029b170-c00000000029b370: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177f9c)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffe000177f9c-ffffffe0001780b6: ring_buffer_empty (STB_GLOBAL)
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
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198b30)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81198b30-ffffffff81198bf8: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118afd0)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff8118afd0-ffffffff8118b084: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196900)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81196900-ffffffff811969c8: ring_buffer_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ring_buffer_empty(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4510)
Location: kernel/trace/ring_buffer.c:4451
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811a4510-ffffffff811a45d6: ring_buffer_empty (STB_GLOBAL)
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
