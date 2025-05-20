# Function: <code>next_online_pgdat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811ac330)
Location: mm/mmzone.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811ac330-ffffffff811ac376: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811c50e0)
Location: mm/mmzone.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811c50e0-ffffffff811c5126: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811d51f0)
Location: mm/mmzone.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811d51f0-ffffffff811d523a: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811de050)
Location: mm/mmzone.c:17
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811de050-ffffffff811de09b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811f3ad0)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811f3ad0-ffffffff811f3b1b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81214e00)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/nobootmem.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81214e00-ffffffff81214e4b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81227ce0)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81227ce0-ffffffff81227d2b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81237a20)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81237a20-ffffffff81237a6b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81245cd0)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81245cd0-ffffffff81245d1b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81273acd)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81273a60-ffffffff81273aab: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8127e33d)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8127e2d0-ffffffff8127e31b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8128349d)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81283430-ffffffff81283480: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812c169d)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812c1630-ffffffff812c1680: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8131e73f)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8131e690-ffffffff8131e704: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81392237)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:__show_mem
```
**Symbols:**

```
ffffffff813921a0-ffffffff813921fc: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813c4c37)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:reset_all_zones_managed_pages
```
**Symbols:**

```
ffffffff813c4ba0-ffffffff813c4bfc: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813ef657)
Location: mm/mmzone.c:18
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:warn_alloc
  - mm/memblock.c:reset_all_zones_managed_pages
```
**Symbols:**

```
ffffffff813ef5c0-ffffffff813ef61c: next_online_pgdat (STB_GLOBAL)
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
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffff8000102d93f8)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffff8000102d93f8-ffff8000102d9468: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c05004f8)
Location: mm/mmzone.c:18
Inline: True
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c05004f8-c0500514: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c000000000399020)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c000000000399020-c0000000003990b4: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffe0001f3748)
Location: mm/mmzone.c:18
Inline: True
Direct callers:
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffe0001f3748-ffffffe0001f3764: next_online_pgdat (STB_GLOBAL)
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
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123e320)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8123e320-ffffffff8123e36b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81231320)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81231320-ffffffff8123136b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123c0c0)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8123c0c0-ffffffff8123c10b: next_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pglist_data *next_online_pgdat(struct pglist_data *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8124b820)
Location: mm/mmzone.c:18
Inline: False
Direct callers:
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:frag_next
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8124b820-ffffffff8124b86b: next_online_pgdat (STB_GLOBAL)
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
