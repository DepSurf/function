# Function: <code>dma_heap_get_name</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff8181da50)
Location: drivers/dma-buf/dma-heap.c:212
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff8181da50-ffffffff8181da5e: dma_heap_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff818a7e90)
Location: drivers/dma-buf/dma-heap.c:214
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff818a7e90-ffffffff818a7e9e: dma_heap_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff819f1bb0)
Location: drivers/dma-buf/dma-heap.c:214
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff819f1bb0-ffffffff819f1bc4: dma_heap_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f890)
Location: drivers/dma-buf/dma-heap.c:214
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff81b6f890-ffffffff81b6f8a4: dma_heap_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81bc31c0)
Location: drivers/dma-buf/dma-heap.c:214
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff81bc31c0-ffffffff81bc31d4: dma_heap_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *dma_heap_get_name(struct dma_heap *heap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-heap.c (ffffffff81c17930)
Location: drivers/dma-buf/dma-heap.c:214
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
**Symbols:**

```
ffffffff81c17930-ffffffff81c17944: dma_heap_get_name (STB_GLOBAL)
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
