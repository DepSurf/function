# Function: <code>phys_to_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (0)
Location: arch/x86/include/asm/dma-mapping.h:58
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
In arch/x86/kernel/pci-dma.c (ffffffff81034072)
Location: arch/x86/include/asm/dma-mapping.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/kernel/pci-nommu.c (ffffffff810360ec)
Location: arch/x86/include/asm/dma-mapping.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/dma-mapping.h:59
Inline: True
```
```
In lib/swiotlb.c (ffffffff814be218)
Location: arch/x86/include/asm/dma-mapping.h:59
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110d045)
Location: include/linux/dma-direct.h:40
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/dma/swiotlb.c (ffffffff8110e056)
Location: include/linux/dma-direct.h:40
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
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
In kernel/dma/direct.c (ffffffff811187b5)
Location: include/linux/dma-direct.h:41
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff81122c51)
Location: include/linux/dma-direct.h:50
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff8112f091)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff8113daf7)
Location: include/linux/dma-direct.h:44
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113f331)
Location: include/linux/dma-direct.h:44
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
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
In kernel/dma/mapping.c (ffffffff81137dd1)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8113942e)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113aa0c)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817403ca)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff81138e94)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8113a516)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113bd6c)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723e7f)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff8115bce9)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8115d01d)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8115ee6c)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2d0b)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff811858d9)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff81186e97)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81189006)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcf84)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff811c124e)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c2957)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811c53e6)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a303c4)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff811d3cce)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5497)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811d7fb6)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79bd4)
Location: include/linux/dma-direct.h:72
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/mapping.c (ffffffff811e896e)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811ea387)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811ed9f2)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc041)
Location: include/linux/dma-direct.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
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
In kernel/dma/direct.c (ffff800010194a20)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/remap.c (ffff800010197620)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
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
In kernel/dma/direct.c (c03e1830)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (c0000000001f4cb4)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffe000126952)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff81127671)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff8111a0d1)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff81125561)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (ffffffff81131ba1)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
</details>
</li>
</ul>

## Differences
