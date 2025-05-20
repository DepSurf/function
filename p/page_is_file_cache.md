# Function: <code>page_is_file_cache</code>

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
In mm/swap.c (ffffffff8119c9a3)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a02b3)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b55cb)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/compaction.c:acct_isolated
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2cf0)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e01f3)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8181a680)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/migrate.c (ffffffff811f102d)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memcontrol.c (ffffffff811fecfe)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In mm/memory-failure.c (ffffffff812031a6)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/swap.c (ffffffff811b1f2c)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811bca93)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff811d0262)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811de993)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/mempolicy.c (ffffffff811fef11)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81894164)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/migrate.c (ffffffff81212fc0)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff81224b28)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81227c9d)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/swap.c (ffffffff811c258c)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811cd166)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff811e02d8)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee7b5)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/mempolicy.c (ffffffff81210751)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff818c8863)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/migrate.c (ffffffff81225330)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffff81237116)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8123a239)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/swap.c (ffffffff811caa0c)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d5e67)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff811e9f5f)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f973b)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/mempolicy.c (ffffffff8121c1a5)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff818ffe70)
Location: include/linux/mm_inline.h:20
Inline: True
```
```
In mm/migrate.c (ffffffff81230a20)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812383f7)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81242bd7)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81245e32)
Location: include/linux/mm_inline.h:20
Inline: True
Inline callers:
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
In mm/swap.c (ffffffff811df77c)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811eb387)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff812002ba)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211b6b)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mempolicy.c (ffffffff812369d2)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81989fbc)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124e7a3)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff81259841)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81262a17)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81265e6a)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
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
In mm/swap.c (ffffffff81201f7c)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cb5e)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff812216e8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812328b4)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff8123920f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff812599c6)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff819e6719)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812725c9)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8127c835)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812868e9)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8128a2be)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
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
In mm/swap.c (ffffffff812148fc)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121fa1d)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81234745)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812460f7)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff8124d796)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff8126d5d8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff81a21c4f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81286bda)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff81290ee1)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8129b875)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8129f268)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
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
In mm/swap.c (ffffffff812245c4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f188)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81244561)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124d8ad)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81258312)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff8125f79f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff81288b1b)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff8129c591)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a1177)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812aa1dd)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812b6c89)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812b96c1)
Location: include/linux/mm_inline.h:21
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
In mm/swap.c (ffffffff81232354)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d318)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81252a21)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125bde4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff812667e2)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff8126dfaf)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff8129868b)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812abff0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b2587)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812bb74d)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812c8b59)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812cb5c1)
Location: include/linux/mm_inline.h:21
Inline: True
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/swap.c (ffff8000102c11d8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce768)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffff8000102eb2a8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f3194)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffff8000102fd7a0)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffff8000103051f8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffff8000103372c0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/migrate.c (ffff800010352dd0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffff80001035ca40)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffff80001036b7e0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffff8000103703e8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
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
In mm/swap.c (c04ed474)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f8528)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (c050eb78)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0515514)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c051cba4)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (c0523484)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/migrate.c (c0552ab0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (c055d0dc)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (c00000000037c264)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c558)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (c0000000003acaf0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b9c08)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c0000000003c8b50)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (c0000000003d2518)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (c000000000411cb8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (c00000000042e260)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000439938)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (c000000000446934)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (c00000000045b630)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (c0000000004600a8)
Location: include/linux/mm_inline.h:21
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
In mm/swap.c (ffffffe0001e3572)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ec8cc)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffe0001ff912)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffe0002054f8)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffe00020c05c)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffe00021133c)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/migrate.c (ffffffe00023fe00)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffe00024902a)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/swap.c (ffffffff8122a9a4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81235968)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff8124b071)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81254434)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125ee32)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff812665ff)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff81290c6b)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a45d0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812aab67)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812b3d2d)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812c1139)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812c3ba1)
Location: include/linux/mm_inline.h:21
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
In mm/swap.c (ffffffff8121dac4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812289d2)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff8123e011)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81247084)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81251262)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff81258ce1)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff812828eb)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812960a0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129c4c4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812a4aab)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812b2187)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812b4be1)
Location: include/linux/mm_inline.h:21
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
In mm/swap.c (ffffffff81228744)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81233708)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff81248e11)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812521d4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125cbd2)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff8126439f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff8128ea7b)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812a23e0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8977)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812b1b3d)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812bef49)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812c19b1)
Location: include/linux/mm_inline.h:21
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
In mm/swap.c (ffffffff81237ab4)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242c3f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff8125865a)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81261b84)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8126c5b2)
Location: include/linux/mm_inline.h:21
Inline: True
```
```
In mm/mprotect.c (ffffffff81273d5f)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mempolicy.c (ffffffff8129e97b)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/memory_hotplug.c (ffffffff812b2740)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b8c97)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812c1edd)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812cf9c0)
Location: include/linux/mm_inline.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812d246c)
Location: include/linux/mm_inline.h:21
Inline: True
```
</details>
</li>
</ul>

## Differences
