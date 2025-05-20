# Function: <code>is_pci_p2pdma_page</code>

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
In kernel/dma/mapping.c (ffffffff811c12cb)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c2f53)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In mm/gup.c (ffffffff813b1eeb)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5f6c)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
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
In kernel/dma/mapping.c (ffffffff811d3d4b)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5a93)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In mm/gup.c (ffffffff813e6c8b)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b246ec)
Location: include/linux/memremap.h:171
Inline: True
Inline callers:
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
In kernel/dma/mapping.c (ffffffff811e89eb)
Location: include/linux/memremap.h:172
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811eaa13)
Location: include/linux/memremap.h:172
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In mm/gup.c (ffffffff8141191b)
Location: include/linux/memremap.h:172
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:try_grab_page
  - mm/gup.c:try_grab_folio
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b35c)
Location: include/linux/memremap.h:172
Inline: True
Inline callers:
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/pci.c (0)
Location: include/linux/mm.h:1004
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
In drivers/nvme/host/pci.c (0)
Location: include/linux/mm.h:1004
Inline: True
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
