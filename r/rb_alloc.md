# Function: <code>rb_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81185d70)
Location: kernel/events/ring_buffer.c:622
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81185d70-ffffffff81185ee6: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81198030)
Location: kernel/events/ring_buffer.c:693
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81198030-ffffffff811981a8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a7a10)
Location: kernel/events/ring_buffer.c:693
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff811a7a10-ffffffff811a7b88: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811af1b0)
Location: kernel/events/ring_buffer.c:705
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff811af1b0-ffffffff811af318: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c2d70)
Location: kernel/events/ring_buffer.c:716
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff811c2d70-ffffffff811c2ed8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e3100)
Location: kernel/events/ring_buffer.c:718
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff811e3100-ffffffff811e3248: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f3590)
Location: kernel/events/ring_buffer.c:728
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff811f3590-ffffffff811f3706: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120b280)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8120b280-ffffffff8120b3f8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81218560)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81218560-ffffffff812186d8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812440c0)
Location: kernel/events/ring_buffer.c:801
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff812440c0-ffffffff812442aa: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124e750)
Location: kernel/events/ring_buffer.c:803
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8124e750-ffffffff8124e952: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81253050)
Location: kernel/events/ring_buffer.c:805
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81253050-ffffffff8125326f: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128e940)
Location: kernel/events/ring_buffer.c:805
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8128e940-ffffffff8128eb84: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e3830)
Location: kernel/events/ring_buffer.c:805
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff812e3830-ffffffff812e3a76: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134bee0)
Location: kernel/events/ring_buffer.c:808
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8134bee0-ffffffff8134c126: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137cf30)
Location: kernel/events/ring_buffer.c:808
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8137cf30-ffffffff8137d176: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a6190)
Location: kernel/events/ring_buffer.c:815
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff813a6190-ffffffff813a63d6: rb_alloc (STB_GLOBAL)
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
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a2fc8)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffff8000102a2fc8-ffff8000102a3170: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d2b78)
Location: kernel/events/ring_buffer.c:866
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
c04d2b78-c04d2c98: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000355380)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
c000000000355380-c000000000355600: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d1880)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffe0001d1880-ffffffe0001d19ee: rb_alloc (STB_GLOBAL)
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
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81210bb0)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81210bb0-ffffffff81210d28: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81203940)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff81203940-ffffffff81203ab8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120e950)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8120e950-ffffffff8120eac8: rb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer *rb_alloc(int nr_pages, long int watermark, int cpu, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121d860)
Location: kernel/events/ring_buffer.c:757
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8121d860-ffffffff8121d9d8: rb_alloc (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>struct ring_buffer *</code> ➡️ <code>struct perf_buffer *</code>
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
