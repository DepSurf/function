# Function: <code>swiotlb_map_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814126d0)
Location: lib/swiotlb.c:738
Inline: False
```
**Symbols:**

```
ffffffff814126d0-ffffffff81412876: swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a420)
Location: lib/swiotlb.c:738
Inline: False
```
**Symbols:**

```
ffffffff8145a420-ffffffff8145a5a1: swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478f20)
Location: lib/swiotlb.c:792
Inline: False
```
**Symbols:**

```
ffffffff81478f20-ffffffff8147905c: swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482280)
Location: lib/swiotlb.c:792
Inline: False
```
**Symbols:**

```
ffffffff81482280-ffffffff814823bd: swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be200)
Location: lib/swiotlb.c:837
Inline: False
```
**Symbols:**

```
ffffffff814be200-ffffffff814be385: swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
dma_addr_t swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e020)
Location: kernel/dma/swiotlb.c:801
Inline: False
```
**Symbols:**

```
ffffffff8110e020-ffffffff8110e1b3: swiotlb_map_page (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
</ul>
