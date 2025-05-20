# Function: <code>bounce_unmap_page</code>

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
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eddbb)
Location: drivers/iommu/intel-iommu.c:3945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
```
**Symbols:**

```
ffffffff816edd80-ffffffff816edd90: bounce_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a5e66)
Location: drivers/iommu/intel/iommu.c:3819
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff817a4220-ffffffff817a4230: bounce_unmap_page (STB_LOCAL)
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
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b352b)
Location: drivers/iommu/intel-iommu.c:3945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
```
**Symbols:**

```
ffffffff816b34f0-ffffffff816b3500: bounce_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816911eb)
Location: drivers/iommu/intel-iommu.c:3945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
```
**Symbols:**

```
ffffffff816911b0-ffffffff816911c0: bounce_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1a7b)
Location: drivers/iommu/intel-iommu.c:3945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
```
**Symbols:**

```
ffffffff816e1a40-ffffffff816e1a50: bounce_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bounce_unmap_page(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fc09b)
Location: drivers/iommu/intel-iommu.c:3945
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
```
**Symbols:**

```
ffffffff816fc060-ffffffff816fc070: bounce_unmap_page (STB_LOCAL)
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
