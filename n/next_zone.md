# Function: <code>next_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811ac380)
Location: mm/mmzone.c:29
Inline: False
Direct callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:snapshot_write_next
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
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
  - mm/page_alloc.c:drain_pages
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:cpu_vm_stats_fold
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811ac380-ffffffff811ac3ab: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811c5130)
Location: mm/mmzone.c:29
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff811c5130-ffffffff811c515b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811d5240)
Location: mm/mmzone.c:29
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff811d5240-ffffffff811d526b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811de0a0)
Location: mm/mmzone.c:29
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff811de0a0-ffffffff811de0cb: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811f3b20)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/madvise.c:SyS_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff811f3b20-ffffffff811f3b4b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81214e50)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81214e50-ffffffff81214e7b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81227d30)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81227d30-ffffffff81227d5b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81237a70)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81237a70-ffffffff81237a9b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81245d20)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81245d20-ffffffff81245d4b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81273ab0)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:madvise_inject_error
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff81273ab0-ffffffff81273b13: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8127e320)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8127e320-ffffffff8127e383: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81283480)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff81283480-ffffffff812834e8: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812c1680)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff812c1680-ffffffff812c16e8: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8131e710)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff8131e710-ffffffff8131e7ae: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81392210)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:page_alloc_init_late
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff81392210-ffffffff8139228e: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813c4c10)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:page_alloc_init_late
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_mem_available
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813c4c10-ffffffff813c4c8e: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813ef630)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
  - kernel/power/snapshot.c:create_mem_extents
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:page_alloc_init_late
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_mem_available
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_online
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_pcp_cacheinfo
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:drain_local_pages
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/huge_memory.c:split_huge_pages_all
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/page_reporting.c:page_reporting_process
```
**Symbols:**

```
ffffffff813ef630-ffffffff813ef6ae: next_zone (STB_GLOBAL)
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
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffff8000102d9468)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__arm64_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffff8000102d9468-ffff8000102d94b0: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c0500514)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_highmem_pages
  - kernel/power/snapshot.c:count_free_highmem_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/highmem.c:nr_free_highpages
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
```
**Symbols:**

```
c0500514-c0500540: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c0000000003990c0)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__se_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
c0000000003990c0-c0000000003990f8: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffe0001f3764)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
```
**Symbols:**

```
ffffffe0001f3764-ffffffe0001f37a2: next_zone (STB_GLOBAL)
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
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123e370)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff8123e370-ffffffff8123e39b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81231370)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81231370-ffffffff8123139b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123c110)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff8123c110-ffffffff8123c13b: next_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct zone *next_zone(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8124b870)
Location: mm/mmzone.c:30
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - mm/vmstat.c:need_update
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_mem_available
  - mm/page_alloc.c:drain_all_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/madvise.c:__do_sys_madvise
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff8124b870-ffffffff8124b89b: next_zone (STB_GLOBAL)
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
