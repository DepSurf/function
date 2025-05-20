# Function: <code>zone_page_state</code>

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
In kernel/power/snapshot.c (ffffffff810d17a4)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_save
```
```
In mm/page_alloc.c (ffffffff81191810)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/page-writeback.c (ffffffff8119aeb5)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
  - mm/page-writeback.c:zone_dirty_ok
```
```
In mm/vmscan.c (ffffffff811a0195)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/vmscan.c:zone_pagecache_reclaimable
  - mm/vmscan.c:zone_pagecache_reclaimable
  - mm/vmscan.c:zone_pagecache_reclaimable
  - mm/vmscan.c:zone_pagecache_reclaimable
  - mm/vmscan.c:zone_pagecache_reclaimable
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:zone_reclaimable
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:zone_reclaim
```
```
In mm/vmstat.c (ffffffff811ac92a)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:node_page_state
  - mm/vmstat.c:node_page_state
```
```
In mm/compaction.c (ffffffff811b5d84)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff811b9edf)
Location: include/linux/vmstat.h:130
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
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
In kernel/power/snapshot.c (ffffffff810d6905)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811ab883)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff811aff30)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff811b83b0)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/vmstat.c (ffffffff811c5ead)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff811d0ecb)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff810dd475)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811bbe6e)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff811c05f0)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff811c89f0)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/vmscan.c:pfmemalloc_watermark_ok
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff811d5f9d)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff811e0eeb)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff810dc555)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811c4543)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff811c8740)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff811d16e8)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff811deccc)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff811eabdb)
Location: include/linux/vmstat.h:146
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff810e4775)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811d9347)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff811dd5a0)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff811e6b88)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff811f489c)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81200f4b)
Location: include/linux/vmstat.h:186
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff810ed749)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff811fb4ab)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff811feb16)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff81207fad)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff81215b0c)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81222355)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff810f8db1)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page_alloc.c (ffffffff8120dd5a)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
```
In mm/page-writeback.c (ffffffff812113c9)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8121ab2e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff81228a09)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff812353a5)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
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
In kernel/power/snapshot.c (ffffffff8110142b)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81220a09)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8122a3da)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff81238717)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81246415)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff8127421f)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff8110d85e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff8122e4b9)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8123820d)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff81246a07)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff812548f5)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81283036)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81118a05)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff8125b559)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff812642e9)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff81274356)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81283885)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff812b50cf)
Location: include/linux/vmstat.h:205
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81bdfe9c)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81265979)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8126ed0a)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff8127eba6)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff8128d925)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81be842b)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81bd1ea3)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff8126a477)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff81273e35)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff81283d46)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81292f55)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81bda22e)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81caab5d)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff812a7127)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff812b199b)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff812c2469)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff812d3375)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81cbe22d)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81e5af84)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff812ff8c7)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff81310430)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff8131f546)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81332165)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81e70156)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff811874a4)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81369c37)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff81383a90)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff813930a6)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff813a8e35)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff813edf43)
Location: include/linux/vmstat.h:201
Inline: True
Inline callers:
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81198634)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff8139bdd7)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff813b3570)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff813c59e6)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff813dbff5)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff813de296)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
```
```
In mm/page_alloc.c (ffffffff8141b89c)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff811a74b5)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff813c5ab7)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff813dcb61)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmscan.c:get_scan_count
```
```
In mm/vmstat.c (ffffffff813f03e6)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff81405f25)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/show_mem.c (ffffffff81408086)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
```
```
In mm/page_alloc.c (ffffffff814488dc)
Location: include/linux/vmstat.h:207
Inline: True
Inline callers:
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:try_to_accept_memory
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:free_unref_page_commit
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
In mm/page-writeback.c (ffff8000102bd3fc)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffff8000102c8f8c)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffff8000102d9cf8)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffff8000102ebdbc)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffff8000103198e4)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (c03c05a8)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:count_free_highmem_pages
```
```
In mm/page-writeback.c (c04e98ac)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:global_dirtyable_memory
  - mm/page-writeback.c:global_dirtyable_memory
  - mm/page-writeback.c:global_dirtyable_memory
```
```
In mm/vmscan.c (c04f2e94)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (c05009b8)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/compaction.c (c050fdf0)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/highmem.c (c0515e94)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/highmem.c:nr_free_highpages
```
```
In mm/page_alloc.c (c05342dc)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In mm/page-writeback.c (c00000000037603c)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (c0000000003852d0)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (c00000000039a3b0)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (c0000000003af53c)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (c0000000003ec57c)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In mm/page-writeback.c (ffffffe0001e0142)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffe0001e8498)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffe0001f3d90)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/compaction.c (ffffffe00020080a)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffe00021f4aa)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81105a7e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81226b09)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8123085d)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123f057)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff8124cf45)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff8127b686)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff810f6d1e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81219c79)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8122391d)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff81232057)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff8123fee5)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff8126d566)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff81103d2e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff812248a9)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8122e5fd)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8123cdf7)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff8124ace5)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81279426)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
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
In kernel/power/snapshot.c (ffffffff8110f11e)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
```
In mm/page-writeback.c (ffffffff81233b79)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
```
```
In mm/vmscan.c (ffffffff8123d9ed)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/vmstat.c (ffffffff8124c527)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:sum_zone_node_page_state
```
```
In mm/compaction.c (ffffffff8125a565)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
```
In mm/page_alloc.c (ffffffff81289016)
Location: include/linux/vmstat.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:show_free_areas
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__zone_watermark_ok
  - mm/page_alloc.c:__isolate_free_page
```
</details>
</li>
</ul>

## Differences
