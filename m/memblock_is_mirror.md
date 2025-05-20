# Function: <code>memblock_is_mirror</code>

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
Location: include/linux/memblock.h:182
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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:191
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:191
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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:191
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:191
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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:175
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:175
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
In mm/page_alloc.c (0)
Location: include/linux/memblock.h:175
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/memblock.h:175
Inline: True
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
In mm/page_alloc.c (ffffffff82701ca7)
Location: include/linux/memblock.h:175
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff819ea7cb)
Location: include/linux/memblock.h:175
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In mm/page_alloc.c (ffffffff828b879e)
Location: include/linux/memblock.h:216
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff81a25a2d)
Location: include/linux/memblock.h:216
Inline: True
Inline callers:
  - mm/memblock.c:__next_mem_range_rev
  - mm/memblock.c:__next_mem_range
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
In mm/page_alloc.c (ffffffff828d58ab)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff812745b9)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff828ddd1f)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff812833c9)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff82cfaff9)
Location: include/linux/memblock.h:208
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff812b541c)
Location: include/linux/memblock.h:208
Inline: True
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
In mm/page_alloc.c (ffffffff82fe7c6e)
Location: include/linux/memblock.h:241
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memblock.c (ffffffff812c04f1)
Location: include/linux/memblock.h:241
Inline: True
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
In mm/page_alloc.c (ffffffff831f23d0)
Location: include/linux/memblock.h:241
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
```
In mm/memblock.c (ffffffff812c5c92)
Location: include/linux/memblock.h:241
Inline: True
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
In mm/page_alloc.c (ffffffff832d820b)
Location: include/linux/memblock.h:242
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
```
In mm/memblock.c (ffffffff8130a5a1)
Location: include/linux/memblock.h:242
Inline: True
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
In mm/page_alloc.c (ffffffff8348d6fb)
Location: include/linux/memblock.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:memmap_init_range
```
```
In mm/memblock.c (ffffffff81373084)
Location: include/linux/memblock.h:253
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In mm/page_alloc.c (ffffffff83ebf6f3)
Location: include/linux/memblock.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:zone_absent_pages_in_node
  - mm/page_alloc.c:memmap_init_range
```
```
In mm/memblock.c (ffffffff813f07f4)
Location: include/linux/memblock.h:253
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In mm/mm_init.c (ffffffff836e0cf8)
Location: include/linux/memblock.h:252
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff81424384)
Location: include/linux/memblock.h:252
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In mm/mm_init.c (ffffffff839135f8)
Location: include/linux/memblock.h:259
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:calculate_node_totalpages
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memblock.c (ffffffff814511a4)
Location: include/linux/memblock.h:259
Inline: True
Inline callers:
  - mm/memblock.c:should_skip_region
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
In mm/page_alloc.c (ffff800011456a84)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffff80001031b6a4)
Location: include/linux/memblock.h:209
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
In mm/memblock.c (c0535600)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (c00000000137f95c)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (c0000000003eefd0)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffe000015728)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffe0002204bc)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff828c6bd3)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff8127ba19)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff828bf2f8)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff8126d8f9)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff828d9953)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff812797b9)
Location: include/linux/memblock.h:209
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
In mm/page_alloc.c (ffffffff828ded74)
Location: include/linux/memblock.h:209
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/memblock.c (ffffffff812893a9)
Location: include/linux/memblock.h:209
Inline: True
```
</details>
</li>
</ul>

## Differences
