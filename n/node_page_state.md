# Function: <code>node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811adda0)
Location: mm/vmstat.c:598
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811adda0-ffffffff811ade10: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5eb2)
Location: mm/vmstat.c:807
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811c70f0-ffffffff811c7114: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5fa2)
Location: mm/vmstat.c:807
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811d7210-ffffffff811d7234: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dee9e)
Location: mm/vmstat.c:807
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811e0070-ffffffff811e0094: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f4ae2)
Location: mm/vmstat.c:991
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811f6000-ffffffff811f6024: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215d68)
Location: mm/vmstat.c:991
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81217290-ffffffff812172b4: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81228c6d)
Location: mm/vmstat.c:991
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8122a1a0-ffffffff8122a1c4: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81238966)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81239e30-ffffffff81239e54: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81246c56)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81248130-ffffffff81248154: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812745b5)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff812762b0-ffffffff812762d4: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81280be0)
Location: mm/vmstat.c:1017
Inline: False
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81280be0-ffffffff81280c04: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81285ce0)
Location: mm/vmstat.c:1029
Inline: False
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81285ce0-ffffffff81285d01: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c4f40)
Location: mm/vmstat.c:1035
Inline: False
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff812c4f40-ffffffff812c4f61: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81322480)
Location: mm/vmstat.c:1036
Inline: False
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81322480-ffffffff813224ab: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81396650)
Location: mm/vmstat.c:1023
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
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
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81396650-ffffffff8139669b: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c9580)
Location: mm/vmstat.c:1024
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
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
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:si_meminfo_node
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813c9580-ffffffff813c95cb: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f3f10)
Location: mm/vmstat.c:1027
Inline: False
Direct callers:
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:__acct_reclaim_writeback
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
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
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:si_meminfo_node
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813f3f10-ffffffff813f3f5b: node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102d9fc8)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffff8000102dcb58-ffff8000102dcb90: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039a744)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
c00000000039c770-c00000000039c794: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123f2a6)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81240780-ffffffff812407a4: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812322a6)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81233780-ffffffff812337a4: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d046)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8123e520-ffffffff8123e544: node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124c776)
Location: mm/vmstat.c:992
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
Direct callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:node_dirty_ok
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:node_pagecache_reclaimable
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
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
  - mm/page_alloc.c:si_meminfo_node
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8124dc50-ffffffff8124dc74: node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pglist_data *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>int node</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum zone_stat_item item</code> ➡️ <code>enum node_stat_item item</code>
</li>
</ul>
</details>
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
