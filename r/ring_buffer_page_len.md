# Function: <code>ring_buffer_page_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114a390)
Location: kernel/trace/ring_buffer.c:332
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
**Symbols:**

```
ffffffff8114a390-ffffffff8114a39e: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152df0)
Location: kernel/trace/ring_buffer.c:332
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
**Symbols:**

```
ffffffff81152df0-ffffffff81152dfe: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cde0)
Location: kernel/trace/ring_buffer.c:332
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
**Symbols:**

```
ffffffff8115cde0-ffffffff8115cdee: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115fe10)
Location: kernel/trace/ring_buffer.c:333
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
**Symbols:**

```
ffffffff8115fe10-ffffffff8115fe1e: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116ced0)
Location: kernel/trace/ring_buffer.c:334
Inline: False
```
**Symbols:**

```
ffffffff8116ced0-ffffffff8116cee3: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117bed0)
Location: kernel/trace/ring_buffer.c:361
Inline: False
```
**Symbols:**

```
ffffffff8117bed0-ffffffff8117bede: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t ring_buffer_page_len(void *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188fd0)
Location: kernel/trace/ring_buffer.c:362
Inline: False
```
**Symbols:**

```
ffffffff81188fd0-ffffffff81188fde: ring_buffer_page_len (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
