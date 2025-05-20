# Function: <code>unmap_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412880)
Location: lib/swiotlb.c:784
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff81412880-ffffffff814128a5: unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a5b0)
Location: lib/swiotlb.c:784
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff8145a5b0-ffffffff8145a5d5: unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81479060)
Location: lib/swiotlb.c:839
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff81479060-ffffffff81479085: unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/swiotlb.c (ffffffff814823d1)
Location: lib/swiotlb.c:839
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_unmap_page
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff814823c0-ffffffff814823c6: unmap_single.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be390)
Location: lib/swiotlb.c:884
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff814be390-ffffffff814be3c3: unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e1c0)
Location: kernel/dma/swiotlb.c:847
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_unmap_page
```
**Symbols:**

```
ffffffff8110e1c0-ffffffff8110e204: unmap_single (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
