# Function: <code>dma_sync_single_range_for_device</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3a58a)
Location: include/linux/dma-mapping.h:610
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9aba)
Location: include/linux/dma-mapping.h:610
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d2fb)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb93d5)
Location: include/linux/dma-mapping.h:296
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a2411b)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba83d5)
Location: include/linux/dma-mapping.h:339
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad9532)
Location: include/linux/dma-mapping.h:347
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c75c45)
Location: include/linux/dma-mapping.h:347
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c5a7a5)
Location: include/linux/dma-mapping.h:347
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e19f25)
Location: include/linux/dma-mapping.h:347
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e10905)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1345)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
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
In net/core/page_pool.c (ffffffff81e842af)
Location: include/linux/dma-mapping.h:353
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206d565)
Location: include/linux/dma-mapping.h:353
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
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
In drivers/virtio/virtio_ring.c (ffffffff81aa5ef9)
Location: include/linux/dma-mapping.h:358
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_device
```
```
In net/core/page_pool.c (ffffffff81f4491b)
Location: include/linux/dma-mapping.h:358
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
  - net/core/page_pool.c:page_pool_dma_map
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141405)
Location: include/linux/dma-mapping.h:358
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/omap-iommu.c (c09c4170)
Location: include/linux/dma-mapping.h:605
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc_large
  - drivers/iommu/omap-iommu.c:iopte_alloc_page
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/tegra-smmu.c (c09c85b4)
Location: include/linux/dma-mapping.h:605
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte
  - drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde
```
</details>
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
