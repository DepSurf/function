# Function: <code>swiotlb_find_pool</code>

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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_tlb_pool *swiotlb_find_pool(struct device *dev, phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811ed080)
Location: kernel/dma/swiotlb.c:771
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_release_slots
  - kernel/dma/swiotlb.c:swiotlb_bounce
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811ed080-ffffffff811ed11d: swiotlb_find_pool (STB_GLOBAL)
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
</ul>
