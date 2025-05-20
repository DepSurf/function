# Function: <code>xa_alloc</code>

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
In drivers/iommu/ioasid.c (ffffffff817931dc)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81829f33)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In net/core/devlink.c (ffffffff81a5332b)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In drivers/iommu/ioasid.c (ffffffff817bfc23)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8183a8e3)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In net/core/devlink.c (ffffffff81a5999b)
Location: include/linux/xarray.h:852
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In drivers/iommu/ioasid.c (ffffffff817a2e3d)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8181db43)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In net/core/devlink.c (ffffffff81a3d45b)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In drivers/iommu/intel/svm.c (ffffffff81821231)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:pasid_private_add
```
```
In drivers/iommu/ioasid.c (ffffffff8182c17d)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/base/memory.c (ffffffff8185cdd6)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dma-buf/dma-heap.c (ffffffff818a7f83)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In net/core/devlink.c (ffffffff81af452b)
Location: include/linux/xarray.h:854
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In drivers/iommu/intel/svm.c (ffffffff81961964)
Location: include/linux/xarray.h:855
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/iommu/ioasid.c (ffffffff8196d368)
Location: include/linux/xarray.h:855
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/base/memory.c (ffffffff819a4054)
Location: include/linux/xarray.h:855
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dma-buf/dma-heap.c (ffffffff819f1cb9)
Location: include/linux/xarray.h:855
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In net/core/devlink.c (ffffffff81c76c4a)
Location: include/linux/xarray.h:855
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In kernel/irq/msi.c (ffffffff811a4181)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca46d)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/iommu/ioasid.c (ffffffff81ad7b4e)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
  - drivers/iommu/ioasid.c:default_alloc
```
```
In drivers/base/memory.c (ffffffff81b1602d)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f954)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81d29bb6)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In net/core/devlink.c (ffffffff81e2f486)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_region_snapshot_id_get
  - net/core/devlink.c:devlink_nl_cmd_region_new
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
In kernel/irq/msi.c (ffffffff811b63f7)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17236)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
```
```
In drivers/base/memory.c (ffffffff81b64d9d)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81bc3284)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81d92dcd)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In net/devlink/leftover.c (ffffffff82032f76)
Location: include/linux/xarray.h:864
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_region_snapshot_id_get
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
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
In kernel/irq/msi.c (ffffffff811c62a7)
Location: include/linux/xarray.h:867
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_insert_desc
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c79c)
Location: include/linux/xarray.h:867
Inline: True
```
```
In drivers/base/memory.c (ffffffff81bb8afc)
Location: include/linux/xarray.h:867
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c17a23)
Location: include/linux/xarray.h:867
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/opp/core.c (ffffffff81e4a747)
Location: include/linux/xarray.h:867
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
```
```
In net/devlink/region.c (ffffffff8210f566)
Location: include/linux/xarray.h:867
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_region_snapshot_id_get
  - net/devlink/region.c:devlink_nl_region_new_doit
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
