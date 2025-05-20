# Function: <code>__dma_to_phys</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e555)
Location: include/linux/dma-direct.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118685)
Location: include/linux/dma-direct.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff81122ac5)
Location: include/linux/dma-direct.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff8112ef05)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e525)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101947f8)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/remap.c (ffff800010197844)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_coherent_to_pfn
  - kernel/dma/remap.c:arch_dma_free
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4edf8)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
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
In kernel/dma/direct.c (c03e1ab0)
Location: arch/arm/include/asm/dma-direct.h:11
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In drivers/firmware/qcom_scm.c (c0c356c8)
Location: arch/arm/include/asm/dma-direct.h:11
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
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
In kernel/dma/direct.c (c0000000001f49d0)
Location: arch/powerpc/include/asm/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffe0001267bc)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff811274e5)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff81119f45)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff811253d5)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
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
In kernel/dma/direct.c (ffffffff81131a15)
Location: include/linux/dma-direct.h:21
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
</details>
</li>
</ul>

## Differences
