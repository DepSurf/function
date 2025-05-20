# Function: <code>phys_to_dma_unencrypted</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137dd1)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8113983c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113aa0c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817403ca)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8113a908)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (ffffffff8113bd6c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723e7f)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8115d83c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8115ee6c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2d0b)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811877ac)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81189006)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dcf84)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c339c)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811c53e6)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a303c4)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5eec)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811d7fb6)
Location: include/linux/dma-direct.h:58
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79bd4)
Location: include/linux/dma-direct.h:58
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
Location: include/linux/dma-direct.h:63
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811eae7c)
Location: include/linux/dma-direct.h:63
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_supported
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811ed9f2)
Location: include/linux/dma-direct.h:63
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_map
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc041)
Location: include/linux/dma-direct.h:63
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
