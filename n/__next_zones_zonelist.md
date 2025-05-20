# Function: <code>__next_zones_zonelist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811c5160)
Location: mm/mmzone.c:55
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811c5160-ffffffff811c519e: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811d5270)
Location: mm/mmzone.c:55
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811d5270-ffffffff811d52ae: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811de0d0)
Location: mm/mmzone.c:55
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff811de0d0-ffffffff811de114: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff811f3b50)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811f3b50-ffffffff811f3bab: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81214e80)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81214e80-ffffffff81214ed9: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81227d60)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81227d60-ffffffff81227db9: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81237aa0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81237aa0-ffffffff81237ae4: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81245d50)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81245d50-ffffffff81245d94: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff81273b20)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff81273b20-ffffffff81273b67: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8127e390)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_zones
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff8127e390-ffffffff8127e3d3: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812834f0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff812834f0-ffffffff81283532: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812c16f0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff812c16f0-ffffffff812c1732: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8131e7b0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff8131e7b0-ffffffff8131e809: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813922a0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff813922a0-ffffffff813922f9: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813c4ca0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
```
**Symbols:**

```
ffffffff813c4ca0-ffffffff813c4cf9: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff813ef6c0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/slub.c:get_any_partial
  - mm/slub.c:get_any_partial
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
```
**Symbols:**

```
ffffffff813ef6c0-ffffffff813ef719: __next_zones_zonelist (STB_GLOBAL)
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
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffff8000102d94b0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff8000102d94b0-ffff8000102d954c: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c0500540)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
```
**Symbols:**

```
c0500540-c0500598: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c000000000399100)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:local_memory_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c000000000399100-c000000000399194: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffe0001f37a2)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
**Symbols:**

```
ffffffe0001f37a2-ffffffe0001f37f0: __next_zones_zonelist (STB_GLOBAL)
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
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123e3a0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8123e3a0-ffffffff8123e3e4: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff812313a0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812313a0-ffffffff812313e4: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8123c140)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8123c140-ffffffff8123c184: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct zoneref *__next_zones_zonelist(struct zoneref *z, enum zone_type highest_zoneidx, nodemask_t *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (ffffffff8124b8a0)
Location: mm/mmzone.c:56
Inline: False
Direct callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/hugetlb.c:dequeue_huge_page_nodemask
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8124b8a0-ffffffff8124b8e4: __next_zones_zonelist (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
