# Function: <code>is_swiotlb_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412382)
Location: lib/swiotlb.c:380
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81413120-ffffffff8141313d: is_swiotlb_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a0c2)
Location: lib/swiotlb.c:380
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff8145ae20-ffffffff8145ae3e: is_swiotlb_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478aa2)
Location: lib/swiotlb.c:410
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81479910-ffffffff8147992e: is_swiotlb_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814823d9)
Location: lib/swiotlb.c:410
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_unmap_page
  - lib/swiotlb.c:swiotlb_free_coherent
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
```
**Symbols:**

```
ffffffff81482c70-ffffffff81482c8d: is_swiotlb_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bd90d)
Location: lib/swiotlb.c:448
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free_coherent
Direct callers:
  - arch/x86/kernel/pci-swiotlb.c:x86_swiotlb_free_coherent
  - arch/x86/mm/mem_encrypt.c:sev_free
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
**Symbols:**

```
ffffffff814becb0-ffffffff814beccd: is_swiotlb_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int is_swiotlb_buffer(phys_addr_t paddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e580)
Location: kernel/dma/swiotlb.c:434
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff8110db10-ffffffff8110db32: is_swiotlb_buffer (STB_GLOBAL)
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
In kernel/dma/direct.c (ffffffff811186be)
Location: include/linux/swiotlb.h:70
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
In kernel/dma/direct.c (ffffffff81122aff)
Location: include/linux/swiotlb.h:67
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
In kernel/dma/direct.c (ffffffff8112ef3f)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816edcbd)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
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
In kernel/dma/direct.c (ffffffff8113e547)
Location: include/linux/swiotlb.h:74
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a4162)
Location: include/linux/swiotlb.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:bounce_unmap_single
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:bounce_sync_single
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
In kernel/dma/mapping.c (ffffffff811381a9)
Location: include/linux/swiotlb.h:75
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113995c)
Location: include/linux/swiotlb.h:75
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdf53)
Location: include/linux/swiotlb.h:75
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
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
In kernel/dma/mapping.c (ffffffff8113926c)
Location: include/linux/swiotlb.h:104
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113aa2f)
Location: include/linux/swiotlb.h:104
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723faa)
Location: include/linux/swiotlb.h:104
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a114b)
Location: include/linux/swiotlb.h:104
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
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
In kernel/dma/mapping.c (ffffffff8115c0f9)
Location: include/linux/swiotlb.h:110
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8115d96f)
Location: include/linux/swiotlb.h:110
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2e48)
Location: include/linux/swiotlb.h:110
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182aacb)
Location: include/linux/swiotlb.h:110
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
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
In kernel/dma/mapping.c (ffffffff81185dc2)
Location: include/linux/swiotlb.h:113
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8118790f)
Location: include/linux/swiotlb.h:113
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd14c)
Location: include/linux/swiotlb.h:113
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196b22b)
Location: include/linux/swiotlb.h:113
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
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
In kernel/dma/mapping.c (ffffffff811c17a5)
Location: include/linux/swiotlb.h:108
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811c351f)
Location: include/linux/swiotlb.h:108
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a3062f)
Location: include/linux/swiotlb.h:108
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad573b)
Location: include/linux/swiotlb.h:108
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
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
In kernel/dma/mapping.c (ffffffff811d4225)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811d606f)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79e44)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23eeb)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
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
In kernel/dma/mapping.c (ffffffff811e8ea9)
Location: include/linux/swiotlb.h:168
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811eb050)
Location: include/linux/swiotlb.h:168
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_need_sync
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc2b6)
Location: include/linux/swiotlb.h:168
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7aaaf)
Location: include/linux/swiotlb.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194804)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
In kernel/dma/direct.c (c0000000001f49ec)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
In kernel/dma/direct.c (ffffffe0001267ca)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
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
In kernel/dma/direct.c (ffffffff8112751f)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b342d)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119f7f)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816910ed)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112540f)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e197d)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
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
In kernel/dma/direct.c (ffffffff81131a4f)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fbf8d)
Location: include/linux/swiotlb.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
