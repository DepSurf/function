# Function: <code>bounce_map_page</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ee141)
Location: drivers/iommu/intel-iommu.c:3929
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff816ee0b0-ffffffff816ee0e8: bounce_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a5e0a)
Location: drivers/iommu/intel/iommu.c:3803
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff817a5d70-ffffffff817a5da8: bounce_map_page (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b38b1)
Location: drivers/iommu/intel-iommu.c:3929
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff816b3820-ffffffff816b3858: bounce_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691571)
Location: drivers/iommu/intel-iommu.c:3929
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff816914e0-ffffffff81691518: bounce_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1e01)
Location: drivers/iommu/intel-iommu.c:3929
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff816e1d70-ffffffff816e1da8: bounce_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t bounce_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fc441)
Location: drivers/iommu/intel-iommu.c:3929
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff816fc3b0-ffffffff816fc3e8: bounce_map_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
