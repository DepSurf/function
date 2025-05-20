# Function: <code>zone_end_pfn</code>

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
In kernel/power/snapshot.c (ffffffff810d082a)
Location: include/linux/mmzone.h:549
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In mm/page_alloc.c (ffffffff81192cb0)
Location: include/linux/mmzone.h:549
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
```
```
In mm/vmstat.c (ffffffff811acfac)
Location: include/linux/mmzone.h:549
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811b5340)
Location: include/linux/mmzone.h:549
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:compact_zone
```
```
In mm/hugetlb.c (0)
Location: include/linux/mmzone.h:549
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81819733)
Location: include/linux/mmzone.h:549
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/base/memory.c (0)
Location: include/linux/mmzone.h:549
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
In kernel/power/snapshot.c (ffffffff810d6a01)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff811ac563)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff811c622e)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811d0fec)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff811fa0a1)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/memory_hotplug.c (ffffffff818938a5)
Location: include/linux/mmzone.h:537
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:zone_can_shift
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/huge_memory.c (ffffffff8121856a)
Location: include/linux/mmzone.h:537
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
In kernel/power/snapshot.c (ffffffff810dd570)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff811bcb40)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff811d637e)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811e103c)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff8120ab6c)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/memory_hotplug.c (ffffffff818c81b0)
Location: include/linux/mmzone.h:511
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:zone_can_shift
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/huge_memory.c (ffffffff8122ab02)
Location: include/linux/mmzone.h:511
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
In kernel/power/snapshot.c (ffffffff810dc652)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff811c4d10)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff811df09f)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811ead31)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff81215e29)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/memory_hotplug.c (ffffffff818ff64f)
Location: include/linux/mmzone.h:515
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/huge_memory.c (ffffffff812366bb)
Location: include/linux/mmzone.h:515
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
In kernel/power/snapshot.c (ffffffff810e4872)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff811d9af4)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff811f4d0f)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812010b1)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff81230a16)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/memory_hotplug.c (ffffffff819895dd)
Location: include/linux/mmzone.h:524
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/huge_memory.c (ffffffff81255683)
Location: include/linux/mmzone.h:524
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
In kernel/power/snapshot.c (ffffffff810ed847)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff811f6b57)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff81215fc2)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81222472)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff81252665)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8126c512)
Location: include/linux/mmzone.h:525
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/huge_memory.c (ffffffff812794cd)
Location: include/linux/mmzone.h:525
Inline: True
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
In kernel/power/snapshot.c (ffffffff810f8eb2)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/page_alloc.c (ffffffff81208ef7)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/vmstat.c (ffffffff81228ec2)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812354c2)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/hugetlb.c (ffffffff812668c5)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81280eb5)
Location: include/linux/mmzone.h:534
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/huge_memory.c (ffffffff8128db50)
Location: include/linux/mmzone.h:534
Inline: True
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
In kernel/power/snapshot.c (ffffffff81101523)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff81238baf)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124654d)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_alloc.c (ffffffff81270247)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81a958f2)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff81281b73)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8129d330)
Location: include/linux/mmzone.h:590
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/huge_memory.c (ffffffff812a84de)
Location: include/linux/mmzone.h:590
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
In kernel/power/snapshot.c (ffffffff8110d956)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff81246e9f)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81254a38)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8127f087)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81acd1d5)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff8129159e)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812acb00)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff812b99be)
Location: include/linux/mmzone.h:591
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
In kernel/power/snapshot.c (ffffffff811184a3)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff812746d6)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812839a1)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812b421e)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81bc5bca)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff812e1b02)
Location: include/linux/mmzone.h:556
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In mm/huge_memory.c (ffffffff812ee51e)
Location: include/linux/mmzone.h:556
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
In kernel/power/snapshot.c (ffffffff81bdf93a)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff8127ef29)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8128da21)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812bfc9e)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81c3eb2d)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff812eca62)
Location: include/linux/mmzone.h:607
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In mm/huge_memory.c (ffffffff812f9b8e)
Location: include/linux/mmzone.h:607
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
In kernel/power/snapshot.c (ffffffff81bd185d)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff812840e9)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81293069)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812c5485)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81c30bfc)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff812c75e8)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In mm/huge_memory.c (ffffffff81300313)
Location: include/linux/mmzone.h:656
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In kernel/power/snapshot.c (ffffffff81caa4b9)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff812c287a)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812d3460)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff813099e5)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81d4f528)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff8130c362)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff81349f66)
Location: include/linux/mmzone.h:692
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
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
In kernel/power/snapshot.c (ffffffff81e5a8dc)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff8131f95d)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8133228f)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff813721be)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81f1f48e)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81374a16)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff813c0996)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In drivers/base/memory.c (ffffffff819a4a85)
Location: include/linux/mmzone.h:713
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
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
In kernel/power/snapshot.c (ffffffff81185db8)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff8139350d)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff813a8f6f)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff813ef9ee)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff820c86e2)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff813f2356)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff81442909)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In drivers/base/memory.c (ffffffff81b16b55)
Location: include/linux/mmzone.h:907
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
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
In kernel/power/snapshot.c (ffffffff81196f92)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff813c5e8d)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/mm_init.c (ffffffff813cc0ce)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/mm_init.c:set_zone_contiguous
```
```
In mm/compaction.c (ffffffff813dc11b)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8142356b)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/shuffle.c (ffffffff8214c962)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81425d96)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff81478233)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In drivers/base/memory.c (ffffffff81b658c5)
Location: include/linux/mmzone.h:1018
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
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
In kernel/power/snapshot.c (ffffffff811a5a72)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:create_mem_extents
```
```
In mm/vmstat.c (ffffffff813f088d)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/mm_init.c (ffffffff813f6a3e)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/mm_init.c:set_zone_contiguous
```
```
In mm/compaction.c (ffffffff81406040)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__compact_finished
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff8145049b)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/shuffle.c (ffffffff8222f472)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81452fd6)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff814a7973)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In drivers/base/memory.c (ffffffff81bb9745)
Location: include/linux/mmzone.h:1028
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
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
In mm/vmstat.c (ffff8000102da214)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffff8000102ebf30)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff8000103152a4)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffff800010da02dc)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffff80001032e754)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/memory_hotplug.c (ffff800010d9ccf8)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffff80001035a140)
Location: include/linux/mmzone.h:591
Inline: True
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
In kernel/power/snapshot.c (c03c0790)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:count_highmem_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (c0501088)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c050ff54)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (c05313b8)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (c15be21c)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
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
In mm/vmstat.c (c00000000039aa6c)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c0000000003af718)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/page_alloc.c (c0000000003e70d0)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (c000000000eecf50)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (c000000000407808)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (c00000000042efe8)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (c000000000443b70)
Location: include/linux/mmzone.h:591
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
In mm/vmstat.c (ffffffe0001f451a)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe000200920)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffe00021bd2c)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffe000047622)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffe00022c7a2)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In kernel/power/snapshot.c (ffffffff81105b76)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff8123f4ef)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124d088)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812776d7)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81a6c045)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff81289b7e)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a50e0)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff812b1f9e)
Location: include/linux/mmzone.h:591
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
In kernel/power/snapshot.c (ffffffff810f6e16)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff812324ef)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81240028)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812695f7)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81a2858c)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff8127b9ae)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81296bb0)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff812a332e)
Location: include/linux/mmzone.h:591
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
In kernel/power/snapshot.c (ffffffff81103e26)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff8123d28f)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124ae28)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81275477)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81ad8455)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff8128798e)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a2ef0)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff812afdae)
Location: include/linux/mmzone.h:591
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
In kernel/power/snapshot.c (ffffffff8110f216)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:count_data_pages
  - kernel/power/snapshot.c:memory_bm_create
```
```
In mm/vmstat.c (ffffffff8124c9bf)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8125a6b8)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81285037)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81ae4910)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/hugetlb.c (ffffffff81297f2b)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812b3180)
Location: include/linux/mmzone.h:591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/huge_memory.c (ffffffff812c00ee)
Location: include/linux/mmzone.h:591
Inline: True
```
</details>
</li>
</ul>

## Differences
