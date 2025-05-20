# Function: <code>memblock_region_memory_base_pfn</code>

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
In mm/memblock.c (0)
Location: include/linux/memblock.h:357
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
In mm/page_alloc.c (ffffffff81fb0510)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff81fb51f4)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
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
In mm/page_alloc.c (ffffffff81fed1e4)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff81ff1bd5)
Location: include/linux/memblock.h:374
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
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
In mm/page_alloc.c (ffffffff820cee51)
Location: include/linux/memblock.h:355
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff820d410b)
Location: include/linux/memblock.h:355
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
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
In mm/page_alloc.c (ffffffff826d786c)
Location: include/linux/memblock.h:370
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff826dcbae)
Location: include/linux/memblock.h:370
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
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
In mm/page_alloc.c (ffffffff82701cad)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff827070d4)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b87a4)
Location: include/linux/memblock.h:503
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828be2f4)
Location: include/linux/memblock.h:503
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828bfcad)
Location: include/linux/memblock.h:503
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d58b1)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828d74c1)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828d9015)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff828ddd2c)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828df932)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828e1468)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff82cfb006)
Location: include/linux/memblock.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff82cfceeb)
Location: include/linux/memblock.h:492
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff82cfea8f)
Location: include/linux/memblock.h:492
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe7c7b)
Location: include/linux/memblock.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f23dd)
Location: include/linux/memblock.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d821e)
Location: include/linux/memblock.h:519
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348d70e)
Location: include/linux/memblock.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebf6fb)
Location: include/linux/memblock.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e0d12)
Location: include/linux/memblock.h:517
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83913612)
Location: include/linux/memblock.h:529
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
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
In arch/arm64/kernel/setup.c (ffff800011434380)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffff800011456a94)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffff80001145a624)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In arch/arm/kernel/setup.c (c1504a68)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/mm/init.c (c15077ec)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:bootmem_init
```
```
In mm/memblock.c (c15328d4)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
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
In arch/powerpc/kernel/fadump.c (c00000000004c094)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/numa.c (c000000001357720)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000013651a8)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_cma_reserve
```
```
In mm/page_alloc.c (c00000000137f970)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (c0000000013821bc)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (c000000001384670)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000003c4c)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:setup_bootmem
```
```
In mm/page_alloc.c (ffffffe000015718)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffe00001704a)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffe000018748)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff828c6be0)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828c87e6)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828ca31c)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff828bf305)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828c0f0b)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828c2a41)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff828d9960)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828db566)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828dd09c)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In mm/page_alloc.c (ffffffff828ded81)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828e0987)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828e24b3)
Location: include/linux/memblock.h:486
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
```
</details>
</li>
</ul>

## Differences
