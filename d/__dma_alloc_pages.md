# Function: <code>__dma_alloc_pages</code>

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
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811387f0)
Location: kernel/dma/mapping.c:480
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff811387f0-ffffffff81138853: __dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b6d0)
Location: kernel/dma/mapping.c:545
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff8115b6d0-ffffffff8115b733: __dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185150)
Location: kernel/dma/mapping.c:539
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff81185150-ffffffff811851fe: __dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0910)
Location: kernel/dma/mapping.c:554
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff811c0910-ffffffff811c09db: __dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3400)
Location: kernel/dma/mapping.c:558
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff811d3400-ffffffff811d34cb: __dma_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *__dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8080)
Location: kernel/dma/mapping.c:558
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
  - kernel/dma/mapping.c:dma_alloc_pages
```
**Symbols:**

```
ffffffff811e8080-ffffffff811e814b: __dma_alloc_pages (STB_LOCAL)
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
