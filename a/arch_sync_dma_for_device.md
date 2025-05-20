# Function: <code>arch_sync_dma_for_device</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:72
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:79
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-noncoherent.h:79
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-noncoherent.h:79
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:277
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:277
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:277
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:277
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:277
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:290
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:290
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:290
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:290
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:290
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:293
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:307
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:307
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:307
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:307
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:307
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:370
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:370
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:370
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:370
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:370
Inline: True
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
In kernel/dma/mapping.c (0)
Location: include/linux/dma-map-ops.h:371
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:371
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/dma-map-ops.h:371
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:371
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:371
Inline: True
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
void arch_sync_dma_for_device(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dma-mapping.c (ffff8000100aca88)
Location: arch/arm64/mm/dma-mapping.c:16
Inline: False
Direct callers:
  - arch/arm/xen/mm.c:xen_dma_sync_for_device
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffff8000100aca88-ffff8000100acad4: arch_sync_dma_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-noncoherent.h:81
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
