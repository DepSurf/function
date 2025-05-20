# Function: <code>PageUnevictable</code>

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
In mm/swap.c (ffffffff8119c994)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a2637)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b60cc)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2ce2)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:munlock_vma_page
```
```
In mm/memcontrol.c (ffffffff811fecef)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In fs/proc/task_mmu.c (ffffffff81276a32)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811b1f5b)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811bca5e)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/compaction.c (ffffffff811cff27)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811dea06)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff81224832)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812a4736)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811c25bb)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811cd131)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/compaction.c (ffffffff811dff53)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee826)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff81236e1b)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812ba0af)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811caa3a)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d5def)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/compaction.c (ffffffff811e9cfa)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f97b6)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff812428cc)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812c77fe)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff811df7aa)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811eb30f)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/compaction.c (ffffffff8120004f)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211be6)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff8126270c)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff812eb3fe)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81201e32)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cb31)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff812213f5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81232925)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff812868cc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8131872e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff812147b2)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121f9a6)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81234448)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81246165)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff8129b857)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8132f640)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81224473)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f15b)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81244204)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81258165)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/memcontrol.c (ffffffff812b69a4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81357107)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81232203)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d2eb)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812526c4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81266635)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff812853cb)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff812c8874)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff8136f6d7)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff8125f5a3)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8126588b)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81282af1)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81296c13)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff812b7864)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813b6ea3)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81269bab)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8127029d)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8128d0b0)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a1c48)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff812c27a5)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813c8543)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff8126d8c1)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81276122)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81291b7c)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812a752b)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff812c962b)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff813cf583)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff812a9f31)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b26fe)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812d18d6)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812e8804)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff8130e651)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In fs/proc/task_mmu.c (ffffffff81420963)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81306baf)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
```
```
In mm/vmscan.c (ffffffff8130f47c)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81330f65)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8134a97d)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/madvise.c (ffffffff81377d9a)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff813b9dde)
Location: include/linux/page-flags.h:577
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499848)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/compaction.c (ffffffff813a7f12)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c356d)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/madvise.c (ffffffff813f5655)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffffffff8143c8bb)
Location: include/linux/page-flags.h:556
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152d9c8)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/huge_memory.c (ffffffff81471f12)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81565dcc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/huge_memory.c (ffffffff814a2658)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8159dda3)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffff8000102c11c0)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce6a8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffff8000102eb284)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffff8000102fdd80)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffff80001031f3f8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffff80001036b7c4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffff800010438e38)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (c04ed348)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f84fc)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (c050e908)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c051d048)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (c0537b6c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (c055ce94)
Location: include/linux/page-flags.h:394
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
In mm/swap.c (c00000000037c250)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c52c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (c0000000003ac850)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (c0000000003c936c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (c0000000003f4774)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (c00000000045b30c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (c00000000054c710)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffe0001e355a)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ec8a8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffe0001ff74e)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffe00020c4ac)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffe000220d08)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffe000248e58)
Location: include/linux/page-flags.h:394
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
In mm/swap.c (ffffffff8122a853)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123593b)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8124ad14)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125ec85)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff8127da1b)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff812c0e54)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81367cb7)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff8121d973)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812289a5)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff8123dcb4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff812510b5)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff8126f8be)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff812b1ea8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81358957)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff812285f3)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812336db)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff81248ab4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8125ca25)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff8127b7bb)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff812bec64)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81365787)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In mm/swap.c (ffffffff81237963)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242c12)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff812582e5)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff8126c405)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:clear_page_mlock
```
```
In mm/madvise.c (ffffffff8128b62c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff812cf6e4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/proc/task_mmu.c (ffffffff81378e67)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
</details>
</li>
</ul>

## Differences
