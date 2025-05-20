# Function: <code>get_pfnblock_flags_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194000)
Location: mm/page_alloc.c:6435
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:test_pages_isolated
```
**Symbols:**

```
ffffffff81194000-ffffffff8119405e: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a70f0)
Location: mm/page_alloc.c:395
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811a70f0-ffffffff811a7151: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b74e0)
Location: mm/page_alloc.c:400
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811b74e0-ffffffff811b7541: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bf300)
Location: mm/page_alloc.c:416
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811bf300-ffffffff811bf35f: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d3e10)
Location: mm/page_alloc.c:431
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811d3e10-ffffffff811d3e79: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5140)
Location: mm/page_alloc.c:392
Inline: False
Direct callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811f5140-ffffffff811f51ad: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812074b0)
Location: mm/page_alloc.c:436
Inline: False
Direct callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/memory-failure.c:soft_offline_page
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812074b0-ffffffff8120751c: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d6a0)
Location: mm/page_alloc.c:498
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8126d6a0-ffffffff8126d70a: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127c4c0)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8127c4c0-ffffffff8127c52a: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae850)
Location: mm/page_alloc.c:484
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812ae850-ffffffff812ae8ba: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ba470)
Location: mm/page_alloc.c:488
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812ba470-ffffffff812ba4cc: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf5c0)
Location: mm/page_alloc.c:510
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812bf5c0-ffffffff812bf61f: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(const struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301f80)
Location: mm/page_alloc.c:512
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81301f80-ffffffff81301fdf: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_pfnblock_flags_mask(const struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136e559)
Location: mm/page_alloc.c:502
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_free_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8136a9e0-ffffffff8136aa6b: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_pfnblock_flags_mask(const struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eaa47)
Location: mm/page_alloc.c:563
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_free_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff813e6d00-ffffffff813e6d8b: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_pfnblock_flags_mask(const struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141f998)
Location: mm/page_alloc.c:404
Inline: True
Inline callers:
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_free_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8141be60-ffffffff8141beeb: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_pfnblock_flags_mask(const struct page *page, long unsigned int pfn, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81449b4d)
Location: mm/page_alloc.c:372
Inline: True
Inline callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:free_pcppages_bulk
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:suitable_migration_target
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81446db0-ffffffff81446e3b: get_pfnblock_flags_mask (STB_GLOBAL)
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
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313f50)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/memory-failure.c:soft_offline_page
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffff800010313f50-ffff800010313fd8: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0534920)
Location: mm/page_alloc.c:485
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_pcppages_bulk
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c052f780-c052f7e0: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e5470)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c0000000003e5470-c0000000003e54f8: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021aabc)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffe00021aabc-ffffffe00021ab2e: get_pfnblock_flags_mask (STB_GLOBAL)
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
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274b10)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81274b10-ffffffff81274b7a: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81266a80)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81266a80-ffffffff81266aea: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812728b0)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812728b0-ffffffff8127291a: get_pfnblock_flags_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int get_pfnblock_flags_mask(struct page *page, long unsigned int pfn, long unsigned int end_bitidx, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282360)
Location: mm/page_alloc.c:485
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:perf_trace_mm_page_alloc_extfrag
  - mm/slab_common.c:trace_event_raw_event_mm_page_alloc_extfrag
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/gup.c:__gup_longterm_locked
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/shuffle.c:__shuffle_zone
  - mm/shuffle.c:__shuffle_zone
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81282360-ffffffff812823ca: get_pfnblock_flags_mask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int end_bitidx</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, pfn, end_bitidx, mask</code> ➡️ <code>page, pfn, mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page *page</code> ➡️ <code>const struct page *page</code>
</li>
</ul>
</details>
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
