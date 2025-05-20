# Function: <code>__dma_free_pages</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81139385)
Location: kernel/dma/mapping.c:509
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff81138870-ffffffff811388b6: __dma_free_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c215)
Location: kernel/dma/mapping.c:574
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff8115b750-ffffffff8115b796: __dma_free_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185f25)
Location: kernel/dma/mapping.c:568
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff81185220-ffffffff81185288: __dma_free_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c19a5)
Location: kernel/dma/mapping.c:585
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff811c0a20-ffffffff811c0a88: __dma_free_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d4425)
Location: kernel/dma/mapping.c:589
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff811d3510-ffffffff811d3578: __dma_free_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __dma_free_pages(struct device *dev, size_t size, struct page *page, dma_addr_t dma_handle, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8f45)
Location: kernel/dma/mapping.c:589
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_pages
Direct callers:
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
**Symbols:**

```
ffffffff811e8190-ffffffff811e81f8: __dma_free_pages (STB_LOCAL)
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
