# Function: <code>dma_to_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:78
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:78
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:75
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:75
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:63
Inline: True
```
```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-swiotlb.c (ffffffff8106bd58)
Location: arch/x86/include/asm/dma-mapping.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810802db)
Location: arch/x86/include/asm/dma-mapping.h:64
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_free
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In lib/swiotlb.c (ffffffff814bd8f1)
Location: arch/x86/include/asm/dma-mapping.h:64
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
```
</details>
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
Location: include/linux/dma-direct.h:45
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
Location: include/linux/dma-direct.h:46
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
Location: include/linux/dma-direct.h:55
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
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ef05)
Location: include/linux/dma-direct.h:63
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
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e525)
Location: include/linux/dma-direct.h:49
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
In kernel/dma/mapping.c (ffffffff8113816d)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113991d)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81741593)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff8113923d)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113a9fd)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724119)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff8115c0ca)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8115d93d)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2fa9)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
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
In kernel/dma/mapping.c (ffffffff81185d93)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811878dd)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd236)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
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
In kernel/dma/mapping.c (ffffffff811c1776)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811c34ed)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a306b6)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
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
In kernel/dma/mapping.c (ffffffff811d41f6)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811d603d)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79ec6)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
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
In kernel/dma/mapping.c (ffffffff811e8e66)
Location: include/linux/dma-direct.h:82
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811eb00d)
Location: include/linux/dma-direct.h:82
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_get_sgtable
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc386)
Location: include/linux/dma-direct.h:82
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
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
In kernel/dma/direct.c (ffff8000101947f8)
Location: include/linux/dma-direct.h:63
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
Location: include/linux/dma-direct.h:63
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_coherent_to_pfn
  - kernel/dma/remap.c:arch_dma_free
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4edf8)
Location: include/linux/dma-direct.h:63
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
Location: include/linux/dma-direct.h:63
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In drivers/firmware/qcom_scm.c (c0c356c8)
Location: include/linux/dma-direct.h:63
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
Location: include/linux/dma-direct.h:63
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
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe0001267bc)
Location: include/linux/dma-direct.h:63
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
Location: include/linux/dma-direct.h:63
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
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119f45)
Location: include/linux/dma-direct.h:63
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
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811253d5)
Location: include/linux/dma-direct.h:63
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
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131a15)
Location: include/linux/dma-direct.h:63
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

## Differences
