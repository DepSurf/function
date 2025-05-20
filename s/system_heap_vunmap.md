# Function: <code>system_heap_vunmap</code>

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
void system_heap_vunmap(struct dma_buf *dmabuf, struct dma_buf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183aa20)
Location: drivers/dma-buf/heaps/system_heap.c:271
Inline: False
```
**Symbols:**

```
ffffffff8183aa20-ffffffff8183aa82: system_heap_vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct dma_buf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181dc80)
Location: drivers/dma-buf/heaps/system_heap.c:271
Inline: False
```
**Symbols:**

```
ffffffff8181dc80-ffffffff8181dce2: system_heap_vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct dma_buf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:271
Inline: False
```
**Symbols:**

```
ffffffff818a8470-ffffffff818a84e1: system_heap_vunmap (STB_LOCAL)
ffffffff81d0bc26-ffffffff81d0bc3b: system_heap_vunmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct iosys_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:272
Inline: False
```
**Symbols:**

```
ffffffff819f2210-ffffffff819f228b: system_heap_vunmap (STB_LOCAL)
ffffffff81ed4a7f-ffffffff81ed4a94: system_heap_vunmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct iosys_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:275
Inline: False
```
**Symbols:**

```
ffffffff81b6fff0-ffffffff81b70068: system_heap_vunmap (STB_LOCAL)
ffffffff8209b85b-ffffffff8209b870: system_heap_vunmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct iosys_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:274
Inline: False
```
**Symbols:**

```
ffffffff81bc3920-ffffffff81bc3998: system_heap_vunmap (STB_LOCAL)
ffffffff8211c748-ffffffff8211c75d: system_heap_vunmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void system_heap_vunmap(struct dma_buf *dmabuf, struct iosys_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/heaps/system_heap.c (0)
Location: drivers/dma-buf/heaps/system_heap.c:271
Inline: False
```
**Symbols:**

```
ffffffff81c180c0-ffffffff81c18138: system_heap_vunmap (STB_LOCAL)
ffffffff821fa5e4-ffffffff821fa5f9: system_heap_vunmap.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_buf_map *map</code> ➡️ <code>struct iosys_map *map</code>
</li>
</ul>
</details>
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
