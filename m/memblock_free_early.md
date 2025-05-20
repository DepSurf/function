# Function: <code>memblock_free_early</code>

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
In mm/percpu.c (ffffffff81f88c00)
Location: include/linux/bootmem.h:223
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/sparse.c (ffffffff81f8ca34)
Location: include/linux/bootmem.h:223
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81f8cb6d)
Location: include/linux/bootmem.h:223
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/swiotlb.c (ffffffff81f9ea4f)
Location: include/linux/bootmem.h:223
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init
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
In mm/percpu.c (ffffffff81fb33d9)
Location: include/linux/bootmem.h:227
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81fb676d)
Location: include/linux/bootmem.h:227
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81fb68e2)
Location: include/linux/bootmem.h:227
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/swiotlb.c (ffffffff81fc9efc)
Location: include/linux/bootmem.h:227
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init
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
In mm/percpu.c (ffffffff81fefd96)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81ff3136)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81ff32ab)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/cpumask.c (ffffffff82003ff8)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In lib/swiotlb.c (ffffffff82006f17)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init
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
In mm/percpu.c (ffffffff820d218d)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff820d5865)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff820d59de)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/swiotlb.c (ffffffff820e7f4f)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init
```
```
In lib/cpumask.c (ffffffff8210f199)
Location: include/linux/bootmem.h:228
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In mm/percpu.c (ffffffff826daca3)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff826de48a)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff826de624)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/swiotlb.c (ffffffff826f0d41)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_init
```
```
In lib/cpumask.c (ffffffff8271958a)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff826f82b7)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff827051d1)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff82708995)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff82708b2b)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In lib/cpumask.c (ffffffff82743d45)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828af159)
Location: include/linux/memblock.h:411
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828bc918)
Location: include/linux/memblock.h:411
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff828bfaf7)
Location: include/linux/memblock.h:411
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
```
In lib/cpumask.c (ffffffff828fe066)
Location: include/linux/memblock.h:411
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828c7cba)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828d3e57)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff828d8d5c)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
```
In lib/cpumask.c (ffffffff8291acc6)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828d0298)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828dc2d4)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81acea9f)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82924b35)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff82cf15d2)
Location: include/linux/memblock.h:410
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff82cfa3dd)
Location: include/linux/memblock.h:410
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81bc7489)
Location: include/linux/memblock.h:410
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82d0a945)
Location: include/linux/memblock.h:410
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff82fde01b)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff82fe713e)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81c4018c)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82ff7f39)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff831e8b87)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff831f1861)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81c3224d)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff83202bb0)
Location: include/linux/memblock.h:443
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff832cd09d)
Location: include/linux/memblock.h:444
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff832d71d2)
Location: include/linux/memblock.h:444
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81d50c4d)
Location: include/linux/memblock.h:444
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff832ea3ac)
Location: include/linux/memblock.h:444
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
</details>
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
In arch/arm64/mm/numa.c (ffff800011438910)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:pcpu_fc_free
```
```
In kernel/dma/swiotlb.c (ffff800011447ee4)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffff800011454dfc)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffff800010da05f0)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
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
In arch/arm/mm/init.c (c150783c)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - arch/arm/mm/init.c:mem_init
```
```
In mm/percpu.c (c152e5a0)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dfl_fc_free
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
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
In kernel/dma/swiotlb.c (c00000000136cff4)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (c00000000137d7b0)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (c000000000eed2c0)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
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
In kernel/dma/swiotlb.c (ffffffe00000977e)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffe000012ba4)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dfl_fc_free
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffe000048caa)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
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
In kernel/dma/swiotlb.c (ffffffff828b9149)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828c5188)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81a6d90f)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82909839)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828b169a)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828bd8ad)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81a29e56)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82901b87)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828cbecc)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828d7f08)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81ad9d1f)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff8291f183)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In kernel/dma/swiotlb.c (ffffffff828d12c6)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init
```
```
In mm/percpu.c (ffffffff828dd329)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/sparse.c (ffffffff81ae61d5)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_free
```
```
In lib/cpumask.c (ffffffff82925ba7)
Location: include/linux/memblock.h:404
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
</details>
</li>
</ul>

## Differences
