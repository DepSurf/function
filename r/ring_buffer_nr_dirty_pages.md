# Function: <code>ring_buffer_nr_dirty_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189090)
Location: kernel/trace/ring_buffer.c:555
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81189090-ffffffff811890c8: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196670)
Location: kernel/trace/ring_buffer.c:532
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81196670-ffffffff811966a8: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a27d4)
Location: kernel/trace/ring_buffer.c:533
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811a2040-ffffffff811a2078: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b8e56)
Location: kernel/trace/ring_buffer.c:535
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b9210-ffffffff811b9248: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b67e5)
Location: kernel/trace/ring_buffer.c:771
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b6c20-ffffffff811b6c58: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5a53)
Location: kernel/trace/ring_buffer.c:857
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811b76b0-ffffffff811b76e8: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dfaff)
Location: kernel/trace/ring_buffer.c:857
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff811e18e0-ffffffff811e1918: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216f21)
Location: kernel/trace/ring_buffer.c:893
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81218590-ffffffff812185d3: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261b10)
Location: kernel/trace/ring_buffer.c:895
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81261b10-ffffffff81261b76: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81278b90)
Location: kernel/trace/ring_buffer.c:893
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffff81278b90-ffffffff81278bf6: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81293650)
Location: kernel/trace/ring_buffer.c:702
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:rb_watermark_hit
```
**Symbols:**

```
ffffffff81293650-ffffffff812936b6: ring_buffer_nr_dirty_pages (STB_GLOBAL)
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
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021c478)
Location: kernel/trace/ring_buffer.c:533
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffff80001021c478-ffff80001021c4b0: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045aecc)
Location: kernel/trace/ring_buffer.c:533
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
c045aecc-c045af48: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029fb40)
Location: kernel/trace/ring_buffer.c:533
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
c00000000029fb40-c00000000029fb88: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000179fc2)
Location: kernel/trace/ring_buffer.c:533
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
**Symbols:**

```
ffffffe000179fc2-ffffffe000179fee: ring_buffer_nr_dirty_pages (STB_GLOBAL)
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
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119adf4)
Location: kernel/trace/ring_buffer.c:533
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8119a660-ffffffff8119a698: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118de74)
Location: kernel/trace/ring_buffer.c:533
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8118d6e0-ffffffff8118d718: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198bc4)
Location: kernel/trace/ring_buffer.c:533
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81198430-ffffffff81198468: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6834)
Location: kernel/trace/ring_buffer.c:533
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_wait
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811a6060-ffffffff811a6098: ring_buffer_nr_dirty_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
