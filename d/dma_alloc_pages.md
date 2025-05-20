# Function: <code>dma_alloc_pages</code>

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
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137a00)
Location: kernel/dma/mapping.c:478
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_alloc_noncoherent
```
**Symbols:**

```
ffffffff81137a00-ffffffff81137a5f: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138860)
Location: kernel/dma/mapping.c:498
Inline: False
```
**Symbols:**

```
ffffffff81138860-ffffffff81138870: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b740)
Location: kernel/dma/mapping.c:563
Inline: False
```
**Symbols:**

```
ffffffff8115b740-ffffffff8115b750: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185200)
Location: kernel/dma/mapping.c:557
Inline: False
```
**Symbols:**

```
ffffffff81185200-ffffffff8118521f: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c09f0)
Location: kernel/dma/mapping.c:574
Inline: False
```
**Symbols:**

```
ffffffff811c09f0-ffffffff811c0a0f: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d34e0)
Location: kernel/dma/mapping.c:578
Inline: False
```
**Symbols:**

```
ffffffff811d34e0-ffffffff811d34ff: dma_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *dma_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, enum dma_data_direction dir, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8160)
Location: kernel/dma/mapping.c:578
Inline: False
```
**Symbols:**

```
ffffffff811e8160-ffffffff811e817f: dma_alloc_pages (STB_GLOBAL)
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
