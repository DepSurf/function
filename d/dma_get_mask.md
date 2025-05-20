# Function: <code>dma_get_mask</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811232fc)
Location: include/linux/dma-mapping.h:651
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f73c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4905)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff8113e4c4)
Location: include/linux/dma-mapping.h:742
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792838)
Location: include/linux/dma-mapping.h:742
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819caa32)
Location: include/linux/dma-mapping.h:742
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff811398b4)
Location: include/linux/dma-mapping.h:407
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bef68)
Location: include/linux/dma-mapping.h:407
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f8b)
Location: include/linux/dma-mapping.h:407
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff8113a984)
Location: include/linux/dma-mapping.h:449
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a2649)
Location: include/linux/dma-mapping.h:449
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aef9b)
Location: include/linux/dma-mapping.h:449
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff8115d8b4)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b939)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d596)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff8118784e)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196cc06)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd6c6)
Location: include/linux/dma-mapping.h:429
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff811c344e)
Location: include/linux/dma-mapping.h:434
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad7316)
Location: include/linux/dma-mapping.h:434
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c108)
Location: include/linux/dma-mapping.h:434
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In kernel/dma/direct.c (ffffffff811d5f9e)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b25b02)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea2c8)
Location: include/linux/dma-mapping.h:435
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In kernel/dma/mapping.c (ffffffff811e92e4)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_addressing_limited
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c8c1)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0534)
Location: include/linux/dma-mapping.h:442
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195298)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/iommu/dma-iommu.c (ffff8000108cab50)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80a58)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/dma-mapping.h:656
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c0c64070)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/dma-iommu.c (c000000000050bec)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_sg
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page
```
```
In arch/powerpc/platforms/pseries/vio.c (c000000000102794)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page
```
```
In kernel/dma/direct.c (c0000000001f55b4)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d314)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffe000126f9c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127d7c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895c35)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In kernel/dma/direct.c (ffffffff8111a77c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff81125c0c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113224c)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906395)
Location: include/linux/dma-mapping.h:656
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
</details>
</li>
</ul>

## Differences
