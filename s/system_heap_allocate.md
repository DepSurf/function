# Function: <code>system_heap_allocate</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8182a830)
Location: drivers/dma-buf/heaps/system_heap.c:35
Inline: False
```
**Symbols:**

```
ffffffff8182a830-ffffffff8182a9c1: system_heap_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b1a0)
Location: drivers/dma-buf/heaps/system_heap.c:334
Inline: False
```
**Symbols:**

```
ffffffff8183b1a0-ffffffff8183b54c: system_heap_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e3b0)
Location: drivers/dma-buf/heaps/system_heap.c:334
Inline: False
```
**Symbols:**

```
ffffffff8181e3b0-ffffffff8181e756: system_heap_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:334
Inline: False
```
**Symbols:**

```
ffffffff818a8800-ffffffff818a8dec: system_heap_allocate (STB_LOCAL)
ffffffff81d0bc65-ffffffff81d0bcc8: system_heap_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:335
Inline: False
```
**Symbols:**

```
ffffffff819f25e0-ffffffff819f2d22: system_heap_allocate (STB_LOCAL)
ffffffff81ed4abe-ffffffff81ed4b2f: system_heap_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:338
Inline: False
```
**Symbols:**

```
ffffffff81b70410-ffffffff81b70b40: system_heap_allocate (STB_LOCAL)
ffffffff8209b89a-ffffffff8209b90e: system_heap_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:337
Inline: False
```
**Symbols:**

```
ffffffff81bc3d10-ffffffff81bc4367: system_heap_allocate (STB_LOCAL)
ffffffff8211c787-ffffffff8211c80e: system_heap_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dma_buf *system_heap_allocate(struct dma_heap *heap, long unsigned int len, long unsigned int fd_flags, long unsigned int heap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:334
Inline: False
```
**Symbols:**

```
ffffffff81c18500-ffffffff81c18b93: system_heap_allocate (STB_LOCAL)
ffffffff821fa623-ffffffff821fa6a3: system_heap_allocate.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct dma_buf *</code>
</li>
</ul>
</details>
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
