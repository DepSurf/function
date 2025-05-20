# Function: <code>__memblock_free_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b4a9)
Location: mm/memblock.c:1396
Inline: False
Direct callers:
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff81f8b4a9-ffffffff81f8b4f5: __memblock_free_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb50ed)
Location: mm/memblock.c:1397
Inline: False
Direct callers:
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff81fb50ed-ffffffff81fb5139: __memblock_free_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1ad4)
Location: mm/memblock.c:1397
Inline: False
Direct callers:
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/cpumask.c:free_bootmem_cpumask_var
  - lib/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff81ff1ad4-ffffffff81ff1b20: __memblock_free_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3f4a)
Location: mm/memblock.c:1419
Inline: False
Direct callers:
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/swiotlb.c:swiotlb_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff820d3f4a-ffffffff820d3f9b: __memblock_free_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc9ed)
Location: mm/memblock.c:1437
Inline: False
Direct callers:
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/swiotlb.c:swiotlb_init
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff826dc9ed-ffffffff826dca3e: __memblock_free_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __memblock_free_early(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706f2c)
Location: mm/memblock.c:1447
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_init
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - lib/cpumask.c:free_bootmem_cpumask_var
```
**Symbols:**

```
ffffffff82706f2c-ffffffff82706f7d: __memblock_free_early (STB_GLOBAL)
```
</details>
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
