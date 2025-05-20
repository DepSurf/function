# Function: <code>system_heap_dma_buf_begin_cpu_access</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183ae80)
Location: drivers/dma-buf/heaps/system_heap.c:153
Inline: False
```
**Symbols:**

```
ffffffff8183ae80-ffffffff8183aef3: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e0c0)
Location: drivers/dma-buf/heaps/system_heap.c:153
Inline: False
```
**Symbols:**

```
ffffffff8181e0c0-ffffffff8181e133: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:153
Inline: False
```
**Symbols:**

```
ffffffff818a8580-ffffffff818a8604: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
ffffffff81d0bc50-ffffffff81d0bc65: system_heap_dma_buf_begin_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:154
Inline: False
```
**Symbols:**

```
ffffffff819f2320-ffffffff819f23b0: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
ffffffff81ed4aa9-ffffffff81ed4abe: system_heap_dma_buf_begin_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:155
Inline: False
```
**Symbols:**

```
ffffffff81b70120-ffffffff81b701ad: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
ffffffff8209b885-ffffffff8209b89a: system_heap_dma_buf_begin_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:154
Inline: False
```
**Symbols:**

```
ffffffff81bc3a50-ffffffff81bc3add: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
ffffffff8211c772-ffffffff8211c787: system_heap_dma_buf_begin_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_begin_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:153
Inline: False
```
**Symbols:**

```
ffffffff81c181f0-ffffffff81c1827d: system_heap_dma_buf_begin_cpu_access (STB_LOCAL)
ffffffff821fa60e-ffffffff821fa623: system_heap_dma_buf_begin_cpu_access.cold (STB_LOCAL)
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
