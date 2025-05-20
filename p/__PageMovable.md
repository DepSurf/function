# Function: <code>__PageMovable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b9ee1)
Location: include/linux/page-flags.h:390
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff811cfc59)
Location: include/linux/page-flags.h:390
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff81211d88)
Location: include/linux/page-flags.h:390
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
In mm/vmscan.c (ffffffff811ca571)
Location: include/linux/page-flags.h:406
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff811dfc9a)
Location: include/linux/page-flags.h:406
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff81223ff2)
Location: include/linux/page-flags.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
In mm/page_alloc.c (ffffffff811c0597)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811d3100)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff811e99a5)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory_hotplug.c (ffffffff818ffe63)
Location: include/linux/page-flags.h:409
Inline: True
```
```
In mm/migrate.c (ffffffff8122f920)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff81245d16)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/page_alloc.c (ffffffff811d5077)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff811e8650)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff811ffcf1)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory_hotplug.c (ffffffff81989bc0)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124d420)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff81265d3a)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/page_alloc.c (ffffffff811fa347)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff81209b1c)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81221111)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory_hotplug.c (ffffffff819e670c)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270d9c)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff8128a0b8)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/page_alloc.c (ffffffff8120ca99)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/vmscan.c (ffffffff8121c7f3)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8123415c)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a21929)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812853ae)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff8129f02c)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff8122c447)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81243ef2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff81272e7d)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a92295)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129fa2a)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812ba6e9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff8123a317)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812523b2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff81281ce2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ac9a25)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b0dca)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812cc5c9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff81267663)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81282862)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff812b3fec)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812e0dff)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e6521)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff81301e29)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/vmscan.c (ffffffff812720d3)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8128c980)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff812bfa80)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812ebbff)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812f1a09)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff8130df38)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
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
In mm/vmscan.c (ffffffff812773e7)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81291887)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff812c51e0)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81c2d810)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff812f7c9e)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff81314264)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
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
In mm/vmscan.c (ffffffff812b4d44)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812d111e)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff81309720)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81d4c0f8)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff8134230e)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff8135f685)
Location: include/linux/page-flags.h:507
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
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
In mm/vmscan.c (ffffffff81313592)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81330890)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:PageMovable
```
```
In mm/page_alloc.c (ffffffff8136b651)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81f1baec)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff813b465f)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff813db3dd)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff813de357)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
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
In mm/compaction.c (ffffffff813a74a3)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:PageMovable
```
```
In mm/page_alloc.c (ffffffff813e79a7)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff820c3ad0)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff814344f5)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff814618a3)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff81464fe7)
Location: include/linux/page-flags.h:670
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
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
In mm/compaction.c (ffffffff813dacd8)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:PageMovable
```
```
In mm/page_alloc.c (ffffffff8141ca87)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff82147978)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8146ab00)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
```
```
In mm/memory-failure.c (ffffffff814970c2)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff8149aaaf)
Location: include/linux/page-flags.h:664
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
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
In mm/compaction.c (ffffffff81404bd2)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:PageMovable
```
```
In mm/page_alloc.c (ffffffff81449587)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8222a105)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff814c5959)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff814ca199)
Location: include/linux/page-flags.h:666
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
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
In mm/vmscan.c (ffff8000102cb250)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffff8000102eb024)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffff80001031a424)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/migrate.c (ffff8000103512fc)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffff8000103701a8)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (c04f52ec)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (c050e5e8)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (c053496c)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/migrate.c (c0552878)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
In mm/vmscan.c (c0000000003881e8)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (c0000000003ac478)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (c0000000003ed63c)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (c0000000004308dc)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000437628)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (c000000000461d30)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffe0001ea166)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffe0001ff50a)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffe00021fbb8)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/migrate.c (ffffffe00023fc4e)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
In mm/vmscan.c (ffffffff81232967)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8124aa02)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff8127a332)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a68895)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a93aa)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812c4ba9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff81225a07)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8123d9a2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff8126c222)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a25355)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129ad0a)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812b5be9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff81230707)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812487a2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff812780d2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ad4ca5)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a71ba)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812c29b9)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/vmscan.c (ffffffff8123fb57)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81257fc7)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_alloc.c (ffffffff81287cc2)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ae1180)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b74c5)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff812d3459)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
</details>
</li>
</ul>

## Differences
