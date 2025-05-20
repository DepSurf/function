# Function: <code>arch_sync_dma_for_cpu</code>

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
Location: include/linux/dma-noncoherent.h:61
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
Location: include/linux/dma-noncoherent.h:82
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:89
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-noncoherent.h:89
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
Location: include/linux/dma-map-ops.h:287
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:287
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:287
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:287
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
Location: include/linux/dma-map-ops.h:300
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:300
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:300
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:300
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
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:303
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
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:303
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:303
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
Location: include/linux/dma-map-ops.h:317
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:317
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:317
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:317
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
Location: include/linux/dma-map-ops.h:380
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:380
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:380
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:380
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
Location: include/linux/dma-map-ops.h:381
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/dma-map-ops.h:381
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/dma-map-ops.h:381
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/dma-map-ops.h:381
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
void arch_sync_dma_for_cpu(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/dma-mapping.c (ffff8000100acad8)
Location: arch/arm64/mm/dma-mapping.c:22
Inline: False
Direct callers:
  - arch/arm/xen/mm.c:xen_dma_sync_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffff8000100acad8-ffff8000100acb24: arch_sync_dma_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:91
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
Location: include/linux/dma-noncoherent.h:91
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
