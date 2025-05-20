# Function: <code>memmap_init_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181d194)
Location: mm/page_alloc.c:4468
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8181d194-ffffffff8181d33b: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8189713d)
Location: mm/page_alloc.c:4964
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8189713d-ffffffff818973c7: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cb882)
Location: mm/page_alloc.c:5056
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff818cb882-ffffffff818cbad5: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81902e60)
Location: mm/page_alloc.c:5346
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81902e60-ffffffff8190305b: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198cd84)
Location: mm/page_alloc.c:5321
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff8198cd84-ffffffff8198cefa: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e9610)
Location: mm/page_alloc.c:5460
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff819e9610-ffffffff819e97cc: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a2501e)
Location: mm/page_alloc.c:5650
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a2501e-ffffffff81a251cf: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95424)
Location: mm/page_alloc.c:5837
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a95424-ffffffff81a95624: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accd07)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81accd07-ffffffff81accf07: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum meminit_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc566b)
Location: mm/page_alloc.c:5941
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81bc566b-ffffffff81bc5830: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap *altmap, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e5de)
Location: mm/page_alloc.c:6115
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81c3e5de-ffffffff81c3e762: memmap_init_zone (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fcd8)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffff800010d9fcd8-ffff800010d9fe80: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bdcb4)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
c15bdcb4-c15bdd98: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eec754)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
c000000000eec754-c000000000eeca40: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0000470bc)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
```
**Symbols:**

```
ffffffe0000470bc-ffffffe000047228: memmap_init_zone (STB_GLOBAL)
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
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6bb77)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a6bb77-ffffffff81a6bd77: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a280be)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81a280be-ffffffff81a282be: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad7f87)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81ad7f87-ffffffff81ad8187: memmap_init_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memmap_init_zone(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, enum memmap_context context, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae4447)
Location: mm/page_alloc.c:5855
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
**Symbols:**

```
ffffffff81ae4447-ffffffff81ae4642: memmap_init_zone (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum memmap_context context</code> ➡️ <code>enum meminit_context context</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int zone_end_pfn</code>
</li>
<li>
<b>Param added. </b>
<code>int migratetype</code>
</li>
<li>
<b>Param reordered. </b>
<code>size, nid, zone, start_pfn, context, altmap</code> ➡️ <code>size, nid, zone, start_pfn, zone_end_pfn, context, altmap, migratetype</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
