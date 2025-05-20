# Function: <code>memblock_get_region_node</code>

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
Location: include/linux/memblock.h:262
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:276
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:276
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:261
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memblock.c (0)
Location: include/linux/memblock.h:276
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:276
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:301
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:301
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In arch/x86/mm/numa.c (ffffffff82ce6cf7)
Location: include/linux/memblock.h:323
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff82cfafff)
Location: include/linux/memblock.h:323
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81bc60a3)
Location: include/linux/memblock.h:323
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
```
```
In mm/sparse.c (ffffffff82cfea8f)
Location: include/linux/memblock.h:323
Inline: True
Inline callers:
  - mm/sparse.c:memblocks_present
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
In arch/x86/mm/numa.c (ffffffff82fd4676)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff82fe7c74)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81c3f003)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff831df1f5)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff831f23d6)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81c310d5)
Location: include/linux/memblock.h:356
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff832c274a)
Location: include/linux/memblock.h:357
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff832d8216)
Location: include/linux/memblock.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81d4f9f5)
Location: include/linux/memblock.h:357
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff83474dad)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff8348d706)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81f1f9bc)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:should_skip_region
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff83e9d3af)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/page_alloc.c (ffffffff83ebf6fb)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff820c8a21)
Location: include/linux/memblock.h:373
Inline: True
Inline callers:
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:should_skip_region
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff836c0f3b)
Location: include/linux/memblock.h:372
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/mm_init.c (ffffffff836e1ac9)
Location: include/linux/memblock.h:372
Inline: True
Inline callers:
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff836e675b)
Location: include/linux/memblock.h:372
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:should_skip_region
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In arch/x86/mm/numa.c (ffffffff838f1aab)
Location: include/linux/memblock.h:384
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
```
```
In mm/mm_init.c (ffffffff839146af)
Location: include/linux/memblock.h:384
Inline: True
Inline callers:
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff83919be8)
Location: include/linux/memblock.h:384
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_dump
  - mm/memblock.c:memblock_search_pfn_nid
  - mm/memblock.c:__next_mem_pfn_range
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
  - mm/memblock.c:should_skip_region
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_merge_regions
  - mm/memblock.c:memblock_merge_regions
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:332
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
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
In mm/memblock.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/memblock.h:323
Inline: True
```
</details>
</li>
</ul>

## Differences
