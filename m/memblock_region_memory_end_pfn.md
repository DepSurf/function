# Function: <code>memblock_region_memory_end_pfn</code>

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
Location: include/linux/memblock.h:366
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
In mm/page_alloc.c (ffffffff81897acb)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff81fb51e2)
Location: include/linux/memblock.h:382
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
In mm/page_alloc.c (ffffffff818cbee7)
Location: include/linux/memblock.h:383
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff81ff1bc3)
Location: include/linux/memblock.h:383
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
In mm/page_alloc.c (ffffffff8190345d)
Location: include/linux/memblock.h:364
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff820d40f9)
Location: include/linux/memblock.h:364
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
In mm/page_alloc.c (ffffffff8198d36d)
Location: include/linux/memblock.h:379
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff826dcb9c)
Location: include/linux/memblock.h:379
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
In mm/page_alloc.c (ffffffff819e9c33)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff827070d4)
Location: include/linux/memblock.h:382
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
In mm/page_alloc.c (ffffffff81a250dc)
Location: include/linux/memblock.h:514
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828be2f4)
Location: include/linux/memblock.h:514
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828bfcad)
Location: include/linux/memblock.h:514
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
In mm/page_alloc.c (ffffffff81a95511)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828d74c1)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828d9015)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff81accdf4)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828df932)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828e1468)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff82cfbc60)
Location: include/linux/memblock.h:503
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff82cfceee)
Location: include/linux/memblock.h:503
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff82cfea8c)
Location: include/linux/memblock.h:503
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
In mm/page_alloc.c (ffffffff82fe8680)
Location: include/linux/memblock.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
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
In mm/page_alloc.c (ffffffff831f318d)
Location: include/linux/memblock.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
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
In mm/page_alloc.c (ffffffff832d91ec)
Location: include/linux/memblock.h:530
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
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
In mm/page_alloc.c (ffffffff8348e0eb)
Location: include/linux/memblock.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
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
In mm/page_alloc.c (ffffffff83ebfe8b)
Location: include/linux/memblock.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:memmap_init_range
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
In mm/mm_init.c (ffffffff836e0d31)
Location: include/linux/memblock.h:528
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
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
In mm/mm_init.c (ffffffff83913631)
Location: include/linux/memblock.h:540
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:memmap_init_range
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
In arch/arm64/kernel/setup.c (ffff80001143439c)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In mm/page_alloc.c (ffff800010d9fd7c)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:497
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
In arch/arm/kernel/setup.c (c1504a90)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/mm/init.c (c1507848)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:mem_init
  - arch/arm/mm/init.c:bootmem_init
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:497
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
In arch/powerpc/kernel/fadump.c (c00000000004c0ac)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/numa.c (c00000000135773c)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000013651a8)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_cma_reserve
```
```
In mm/page_alloc.c (c000000000eec8bc)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (c0000000013821bc)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (c000000001384670)
Location: include/linux/memblock.h:497
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
In arch/riscv/mm/init.c (ffffffe000003c70)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:setup_bootmem
```
```
In mm/page_alloc.c (ffffffe00004714c)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffe000017058)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffe000018762)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff81a6bc64)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828c87e6)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828ca31c)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff81a281ab)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828c0f0b)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828c2a41)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff81ad8074)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828db566)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828dd09c)
Location: include/linux/memblock.h:497
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
In mm/page_alloc.c (ffffffff81ae4534)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff828e0987)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/memblock.c:memblock_mem_size
```
```
In mm/sparse.c (ffffffff828e24b3)
Location: include/linux/memblock.h:497
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
```
</details>
</li>
</ul>

## Differences
