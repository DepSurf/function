# Function: <code>zone_managed_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812069b3)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff8121b875)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff812289ff)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:calculate_normal_threshold
```
```
In lib/show_mem.c (ffffffff81a102ed)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff8122b505)
Location: include/linux/mmzone.h:585
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123870f)
Location: include/linux/mmzone.h:585
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/page_alloc.c (ffffffff8126c9e6)
Location: include/linux/mmzone.h:585
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81a7f881)
Location: include/linux/mmzone.h:585
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff812393d5)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff812469ff)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff8127b7f6)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81ab6a81)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff8126a975)
Location: include/linux/mmzone.h:551
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff8127434e)
Location: include/linux/mmzone.h:551
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff812ad916)
Location: include/linux/mmzone.h:551
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In lib/show_mem.c (ffffffff815f16db)
Location: include/linux/mmzone.h:551
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff812753d5)
Location: include/linux/mmzone.h:602
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff8127eb9e)
Location: include/linux/mmzone.h:602
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff812b92d6)
Location: include/linux/mmzone.h:602
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In lib/show_mem.c (ffffffff81bf4d28)
Location: include/linux/mmzone.h:602
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff8127a6f5)
Location: include/linux/mmzone.h:642
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff81283d3e)
Location: include/linux/mmzone.h:642
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff812be7a6)
Location: include/linux/mmzone.h:642
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In lib/show_mem.c (ffffffff81be6c4b)
Location: include/linux/mmzone.h:642
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff812b8755)
Location: include/linux/mmzone.h:678
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff812c245e)
Location: include/linux/mmzone.h:678
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff813010b6)
Location: include/linux/mmzone.h:678
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In lib/show_mem.c (ffffffff81cdfab3)
Location: include/linux/mmzone.h:678
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff81314185)
Location: include/linux/mmzone.h:699
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/vmstat.c (ffffffff8131f52e)
Location: include/linux/mmzone.h:699
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff813686a6)
Location: include/linux/mmzone.h:699
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/migrate.c (ffffffff813b2d86)
Location: include/linux/mmzone.h:699
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In lib/show_mem.c (ffffffff81ea6272)
Location: include/linux/mmzone.h:699
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff81388245)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/vmstat.c (ffffffff8139308e)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff813e4956)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/migrate.c (ffffffff814331eb)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff814428fc)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In lib/show_mem.c (ffffffff8203cf7d)
Location: include/linux/mmzone.h:893
Inline: True
Inline callers:
  - lib/show_mem.c:__show_mem
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
In mm/vmscan.c (ffffffff813ba525)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/vmstat.c (ffffffff813c59ce)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/show_mem.c (ffffffff813debdb)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_meminfo_node
```
```
In mm/page_alloc.c (ffffffff814195b6)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/migrate.c (ffffffff81468b04)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
```
In mm/huge_memory.c (ffffffff81478227)
Location: include/linux/mmzone.h:1004
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/vmscan.c (ffffffff813e3645)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:should_abort_scan
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/vmstat.c (ffffffff813f03ce)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/show_mem.c (ffffffff81408aab)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/show_mem.c:__show_mem
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_meminfo_node
```
```
In mm/page_alloc.c (ffffffff814462f6)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:steal_suitable_fallback
```
```
In mm/migrate.c (ffffffff8149ac3b)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
```
```
In mm/huge_memory.c (ffffffff814a7967)
Location: include/linux/mmzone.h:1014
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In mm/vmscan.c (ffff8000102ca2b8)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffff8000102d9d14)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffff800010312d40)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffff800010d9126c)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (c04f4104)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (c05009d8)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (c052f560)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:__setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (c0e8be00)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (c000000000386c10)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (c00000000039a3b8)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (c0000000003e3f30)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (c000000000ed4774)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffe0001e93e4)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffe0001f3d98)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:calculate_normal_threshold
```
```
In mm/page_alloc.c (ffffffe00021f7c2)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffe0008ba0d2)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff81231a25)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123f04f)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff81273e46)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81a558d1)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff81224ae5)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123204f)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff81265db6)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81a129b1)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff8122f7c5)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123cdef)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff81271be6)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81ac1cc1)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
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
In mm/vmscan.c (ffffffff8123ebf5)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:pgdat_balanced
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8124c51f)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/page_alloc.c (ffffffff81281646)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_min_slab_ratio
  - mm/page_alloc.c:setup_min_unmapped_ratio
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_wmarks
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:setup_per_zone_lowmem_reserve
  - mm/page_alloc.c:calculate_totalreserve_pages
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:build_zonerefs_node
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:get_page_from_freelist
```
```
In lib/show_mem.c (ffffffff81ace191)
Location: include/linux/mmzone.h:586
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
</ul>

## Differences
