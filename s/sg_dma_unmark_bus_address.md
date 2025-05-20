# Function: <code>sg_dma_unmark_bus_address</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2cfa)
Location: include/linux/scatterlist.h:297
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5859)
Location: include/linux/scatterlist.h:297
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d583a)
Location: include/linux/scatterlist.h:322
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b24005)
Location: include/linux/scatterlist.h:322
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea76d)
Location: include/linux/scatterlist.h:322
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7ac05)
Location: include/linux/scatterlist.h:322
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
