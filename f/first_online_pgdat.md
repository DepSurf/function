# Function: <code>first_online_pgdat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811ac2f0)
Location: mm/mmzone.c:12
Inline: False
Direct callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:snapshot_write_next
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:init_per_zone_wmark_min
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:drain_pages
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:cpu_vm_stats_fold
  - fs/proc/meminfo.c:meminfo_proc_show
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811ac2f0-ffffffff811ac321: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811c50a0)
Location: mm/mmzone.c:12
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811c50a0-ffffffff811c50d1: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811d51b0)
Location: mm/mmzone.c:12
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811d51b0-ffffffff811d51e3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811de010)
Location: mm/mmzone.c:12
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811de010-ffffffff811de043: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811f3a90)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff811f3a90-ffffffff811f3ac3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81214dc0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/nobootmem.c:reset_all_zones_managed_pages
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81214dc0-ffffffff81214df3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81227ca0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81227ca0-ffffffff81227cd3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812379e0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812379e0-ffffffff81237a13: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81245c90)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81245c90-ffffffff81245cc3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81273a20)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81273a20-ffffffff81273a53: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8127e290)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8127e290-ffffffff8127e2c3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81283400)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff81283400-ffffffff81283430: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812c1600)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812c1600-ffffffff812c1630: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8131e650)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8131e650-ffffffff8131e68a: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81392150)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
  - lib/show_mem.c:__show_mem
```
**Symbols:**

```
ffffffff81392150-ffffffff8139218a: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813c4b50)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:page_alloc_init_late
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_mem_available
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813c4b50-ffffffff813c4b8a: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813ef570)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:page_alloc_init_late
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_mem_available
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_pcp_cacheinfo
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813ef570-ffffffff813ef5aa: first_online_pgdat (STB_GLOBAL)
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
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffff8000102d93b0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__arm64_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffff8000102d93b0-ffff8000102d93f4: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c05004d8)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_highmem_pages
  - kernel/power/snapshot.c:count_free_highmem_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/highmem.c:nr_free_highpages
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c05004d8-c05004f8: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c000000000398fb0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__se_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
c000000000398fb0-c000000000399014: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffe0001f3726)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffe0001f3726-ffffffe0001f3748: first_online_pgdat (STB_GLOBAL)
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
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123e2e0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8123e2e0-ffffffff8123e313: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812312e0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff812312e0-ffffffff81231313: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123c080)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8123c080-ffffffff8123c0b3: first_online_pgdat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pglist_data *first_online_pgdat();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8124b7e0)
Location: mm/mmzone.c:13
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:frag_start
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memblock.c:reset_all_zones_managed_pages
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
  - lib/show_mem.c:show_mem
```
**Symbols:**

```
ffffffff8124b7e0-ffffffff8124b813: first_online_pgdat (STB_GLOBAL)
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
