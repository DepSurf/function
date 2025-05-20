# Function: <code>__next_mem_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181eb6a)
Location: mm/memblock.c:1079
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8181eb6a-ffffffff8181ebe1: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81899039)
Location: mm/memblock.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81899039-ffffffff818990b0: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd6e1)
Location: mm/memblock.c:1080
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/kernel/e820.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff818cd6e1-ffffffff818cd75b: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81904b3c)
Location: mm/memblock.c:1076
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81904b3c-ffffffff81904bb6: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198eb45)
Location: mm/memblock.c:1076
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8198eb45-ffffffff8198ebbf: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb427)
Location: mm/memblock.c:1084
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff819eb427-ffffffff819eb49c: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a2669f)
Location: mm/memblock.c:1199
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81a2669f-ffffffff81a26714: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96e51)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81a96e51-ffffffff81a96ec6: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace6c1)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ace6c1-ffffffff81ace736: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc70a8)
Location: mm/memblock.c:1203
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81bc70a8-ffffffff81bc7124: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3fdca)
Location: mm/memblock.c:1162
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81c3fdca-ffffffff81c3fe46: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31e8c)
Location: mm/memblock.c:1163
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81c31e8c-ffffffff81c31f08: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d50896)
Location: mm/memblock.c:1198
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81d50896-ffffffff81d50912: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20a0b)
Location: mm/memblock.c:1203
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81f20a0b-ffffffff81f20aba: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca2c0)
Location: mm/memblock.c:1221
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:memmap_init
  - mm/page_alloc.c:memmap_init
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff820ca2c0-ffffffff820ca3b7: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214e550)
Location: mm/memblock.c:1234
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/mm_init.c:node_map_pfn_alignment
  - mm/mm_init.c:node_map_pfn_alignment
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:get_pfn_range_for_nid
  - mm/mm_init.c:get_pfn_range_for_nid
  - mm/mm_init.c:__absent_pages_in_range
  - mm/mm_init.c:__absent_pages_in_range
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff8214e550-ffffffff8214e647: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff822312c0)
Location: mm/memblock.c:1292
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/mm_init.c:node_map_pfn_alignment
  - mm/mm_init.c:node_map_pfn_alignment
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:get_pfn_range_for_nid
  - mm/mm_init.c:get_pfn_range_for_nid
  - mm/mm_init.c:__absent_pages_in_range
  - mm/mm_init.c:__absent_pages_in_range
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:memmap_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/memblock.c:memblock_validate_numa_coverage
  - mm/memblock.c:memblock_validate_numa_coverage
  - mm/sparse.c:sparse_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff822312c0-ffffffff822313b7: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031cdb8)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
```
**Symbols:**

```
ffff80001031cdb8-ffff80001031cec0: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f0bf0)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
```
**Symbols:**

```
c0000000003f0bf0-c0000000003f0cec: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000048872)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
```
**Symbols:**

```
ffffffe000048872-ffffffe0000488ec: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d531)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81a6d531-ffffffff81a6d5a6: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29a78)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81a29a78-ffffffff81a29aed: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad9941)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ad9941-ffffffff81ad99b6: __next_mem_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __next_mem_pfn_range(int *idx, int nid, long unsigned int *out_start_pfn, long unsigned int *out_end_pfn, int *out_nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5df7)
Location: mm/memblock.c:1196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:memblock_find_dma_reserve
  - arch/x86/mm/init.c:init_range_memory_mapping
  - arch/x86/mm/init.c:init_range_memory_mapping
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:find_min_pfn_for_node
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:__absent_pages_in_range
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:get_pfn_range_for_nid
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:sparse_memory_present_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - mm/page_alloc.c:free_bootmem_with_active_regions
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ae5df7-ffffffff81ae5e6c: __next_mem_pfn_range (STB_GLOBAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
