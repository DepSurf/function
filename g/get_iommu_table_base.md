# Function: <code>get_iommu_table_base</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/dma-iommu.c (c0000000000507fc)
Location: arch/powerpc/include/asm/iommu.h:142
Inline: True
Inline callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_get_required_mask
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_dma_supported
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_sg
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_sg
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_page
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_free_coherent
```
```
In arch/powerpc/platforms/pseries/vio.c (c0000000000ff9a0)
Location: arch/powerpc/include/asm/iommu.h:142
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_dev_release
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_probe
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_free_coherent
```
</details>
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
