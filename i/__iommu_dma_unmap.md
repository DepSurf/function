# Function: <code>__iommu_dma_unmap</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817919b0)
Location: drivers/iommu/dma-iommu.c:456
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff817919b0-ffffffff81791aa4: __iommu_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bdba0)
Location: drivers/iommu/dma-iommu.c:488
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff817bdba0-ffffffff817bdcb5: __iommu_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0de0)
Location: drivers/iommu/dma-iommu.c:474
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff817a0de0-ffffffff817a0ef3: __iommu_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:490
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
```
**Symbols:**

```
ffffffff8182a930-ffffffff8182aa65: __iommu_dma_unmap (STB_LOCAL)
ffffffff81d01e4b-ffffffff81d01e5f: __iommu_dma_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:663
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
```
**Symbols:**

```
ffffffff8196b050-ffffffff8196b1b5: __iommu_dma_unmap (STB_LOCAL)
ffffffff81eca2f1-ffffffff81eca310: __iommu_dma_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:674
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
```
**Symbols:**

```
ffffffff81ad5540-ffffffff81ad56a5: __iommu_dma_unmap (STB_LOCAL)
ffffffff82097fc3-ffffffff82097fe2: __iommu_dma_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:707
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
```
**Symbols:**

```
ffffffff81b23cf0-ffffffff81b23e55: __iommu_dma_unmap (STB_LOCAL)
ffffffff82118fd3-ffffffff82118ff2: __iommu_dma_unmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:826
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_free_noncontiguous
```
**Symbols:**

```
ffffffff81b7a8b0-ffffffff81b7aa15: __iommu_dma_unmap (STB_LOCAL)
ffffffff821f6f7f-ffffffff821f6f9e: __iommu_dma_unmap.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __iommu_dma_unmap(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8d78)
Location: drivers/iommu/dma-iommu.c:441
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff8000108c8d78-ffff8000108c8e7c: __iommu_dma_unmap (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
