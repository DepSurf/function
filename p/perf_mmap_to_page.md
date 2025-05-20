# Function: <code>perf_mmap_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81185f50)
Location: kernel/events/ring_buffer.c:766
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81185f50-ffffffff81185fe1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81198200)
Location: kernel/events/ring_buffer.c:839
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81198200-ffffffff8119829a: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a7be0)
Location: kernel/events/ring_buffer.c:839
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff811a7be0-ffffffff811a7c74: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811af370)
Location: kernel/events/ring_buffer.c:851
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff811af370-ffffffff811af404: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c2f30)
Location: kernel/events/ring_buffer.c:862
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff811c2f30-ffffffff811c2fc4: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e32a0)
Location: kernel/events/ring_buffer.c:864
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff811e32a0-ffffffff811e3368: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f3760)
Location: kernel/events/ring_buffer.c:877
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff811f3760-ffffffff811f3828: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120b450)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8120b450-ffffffff8120b4f1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81218730)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81218730-ffffffff812187d1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81244390)
Location: kernel/events/ring_buffer.c:942
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81244390-ffffffff81244431: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124ea40)
Location: kernel/events/ring_buffer.c:944
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8124ea40-ffffffff8124eae1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81253350)
Location: kernel/events/ring_buffer.c:949
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81253350-ffffffff812533f4: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128ec70)
Location: kernel/events/ring_buffer.c:949
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8128ec70-ffffffff8128ed14: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e3b60)
Location: kernel/events/ring_buffer.c:944
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff812e3b60-ffffffff812e3c1c: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134c230)
Location: kernel/events/ring_buffer.c:947
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8134c230-ffffffff8134c2ec: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137d280)
Location: kernel/events/ring_buffer.c:947
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8137d280-ffffffff8137d33c: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct perf_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a64e0)
Location: kernel/events/ring_buffer.c:954
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff813a64e0-ffffffff813a659c: perf_mmap_to_page (STB_GLOBAL)
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
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a3210)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffff8000102a3210-ffff8000102a3304: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d2c98)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
c04d2c98-c04d2d34: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c0000000003556f0)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
c0000000003556f0-c0000000003557d8: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d1a88)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffe0001d1a88-ffffffe0001d1b2c: perf_mmap_to_page (STB_GLOBAL)
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
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81210d80)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81210d80-ffffffff81210e21: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81203b10)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff81203b10-ffffffff81203bb1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120eb20)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8120eb20-ffffffff8120ebc1: perf_mmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *perf_mmap_to_page(struct ring_buffer *rb, long unsigned int pgoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121da30)
Location: kernel/events/ring_buffer.c:906
Inline: False
Direct callers:
  - kernel/events/core.c:perf_mmap_fault
```
**Symbols:**

```
ffffffff8121da30-ffffffff8121dad1: perf_mmap_to_page (STB_GLOBAL)
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
<code>struct ring_buffer *rb</code> ➡️ <code>struct perf_buffer *rb</code>
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
