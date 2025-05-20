# Function: <code>folio_test_lru</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305acc)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/gup.c (ffffffff81337b30)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory_hotplug.c (ffffffff81373f60)
Location: include/linux/page-flags.h:500
Inline: True
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
In mm/swap.c (ffffffff8136f4da)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137879a)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/gup.c (ffffffff813ae92d)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff813bc3ff)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/memory_hotplug.c (ffffffff813f19fc)
Location: include/linux/page-flags.h:479
Inline: True
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
In mm/swap.c (ffffffff813a15fa)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813acd93)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813daedf)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e322d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff813f0c4e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/memory_hotplug.c (ffffffff814257bb)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427ff5)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff81478325)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/page_idle.c (ffffffff814a2ac4)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
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
In mm/swap.c (ffffffff813cb27a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d63c3)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff81404dd9)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140e975)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:collect_longterm_unpinnable_pages
```
```
In mm/memory.c (ffffffff81420605)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/memory_hotplug.c (ffffffff814527a5)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff8146164a)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff814a7a56)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff814afa37)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memory-failure.c (ffffffff814c6592)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
```
```
In mm/page_isolation.c (ffffffff814c9c33)
Location: include/linux/page-flags.h:475
Inline: True
```
```
In mm/page_idle.c (ffffffff814d3954)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
  - mm/page_idle.c:page_idle_get_folio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
