# Function: <code>system_heap_dma_buf_end_cpu_access</code>

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
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183ae00)
Location: drivers/dma-buf/heaps/system_heap.c:174
Inline: False
```
**Symbols:**

```
ffffffff8183ae00-ffffffff8183ae73: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e040)
Location: drivers/dma-buf/heaps/system_heap.c:174
Inline: False
```
**Symbols:**

```
ffffffff8181e040-ffffffff8181e0b3: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:174
Inline: False
```
**Symbols:**

```
ffffffff818a84f0-ffffffff818a8574: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
ffffffff81d0bc3b-ffffffff81d0bc50: system_heap_dma_buf_end_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:175
Inline: False
```
**Symbols:**

```
ffffffff819f2290-ffffffff819f2320: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
ffffffff81ed4a94-ffffffff81ed4aa9: system_heap_dma_buf_end_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:176
Inline: False
```
**Symbols:**

```
ffffffff81b70080-ffffffff81b7010d: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
ffffffff8209b870-ffffffff8209b885: system_heap_dma_buf_end_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:175
Inline: False
```
**Symbols:**

```
ffffffff81bc39b0-ffffffff81bc3a3d: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
ffffffff8211c75d-ffffffff8211c772: system_heap_dma_buf_end_cpu_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int system_heap_dma_buf_end_cpu_access(struct dma_buf *dmabuf, enum dma_data_direction direction);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:174
Inline: False
```
**Symbols:**

```
ffffffff81c18150-ffffffff81c181dd: system_heap_dma_buf_end_cpu_access (STB_LOCAL)
ffffffff821fa5f9-ffffffff821fa60e: system_heap_dma_buf_end_cpu_access.cold (STB_LOCAL)
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
