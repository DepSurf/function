# Function: <code>PageLRU</code>

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
In mm/page_alloc.c (ffffffff8119534a)
Location: include/linux/page-flags.h:214
Inline: True
```
```
In mm/swap.c (ffffffff8119c929)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a2625)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b5ea6)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2f8d)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
```
In mm/memory_hotplug.c (ffffffff8181a442)
Location: include/linux/page-flags.h:214
Inline: True
```
```
In mm/migrate.c (ffffffff811f32ef)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f4c7e)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff811fecbf)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
```
```
In mm/memory-failure.c (ffffffff81202099)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_idle.c (ffffffff81208147)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8128828d)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811a796a)
Location: include/linux/page-flags.h:262
Inline: True
```
```
In mm/swap.c (ffffffff811b3d74)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811bca45)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff811cfc3f)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811de835)
Location: include/linux/page-flags.h:262
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81893ee3)
Location: include/linux/page-flags.h:262
Inline: True
```
```
In mm/migrate.c (ffffffff812130c5)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81218683)
Location: include/linux/page-flags.h:262
Inline: True
```
```
In mm/khugepaged.c (ffffffff8121bfc3)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812247d0)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81227bae)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
  - mm/memory-failure.c:shake_page
```
```
In mm/page_idle.c (ffffffff8122db69)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff812b56f3)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811b7d58)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/swap.c (ffffffff811c4404)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811cd118)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff811dfc80)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811ee655)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff818c85db)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/migrate.c (ffffffff81225435)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8122ac1e)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/khugepaged.c (ffffffff8122d77a)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81236db9)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8123a13b)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
  - mm/memory-failure.c:shake_page
```
```
In mm/page_idle.c (ffffffff812400ae)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff812caf77)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811c0580)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/swap.c (ffffffff811cc848)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d5dd6)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff811e998b)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811f95f5)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff818ffdf1)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/migrate.c (ffffffff81230b03)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8123677c)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/khugepaged.c (ffffffff8123a062)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8124286b)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81245d00)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff8124bf6e)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff812d83db)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811d5060)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/swap.c (ffffffff811e1868)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811eb2f6)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff811ffcd7)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81211a25)
Location: include/linux/page-flags.h:273
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81989ba5)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124c1f0)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255774)
Location: include/linux/page-flags.h:273
Inline: True
```
```
In mm/khugepaged.c (ffffffff81258722)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812626ab)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81265d24)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff8126c328)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff812fcadb)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff811fa354)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/swap.c (ffffffff81202f54)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cb1f)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff812210f7)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81232775)
Location: include/linux/page-flags.h:280
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff819e66aa)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8126fd15)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812795b2)
Location: include/linux/page-flags.h:280
Inline: True
```
```
In mm/khugepaged.c (ffffffff8127d51c)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8128686b)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8128a0a2)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_idle.c (ffffffff81290ec5)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8132a6f8)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_alloc.c (ffffffff8120caa6)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/swap.c (ffffffff812158f4)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121f994)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81234142)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff81245fb5)
Location: include/linux/page-flags.h:289
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81a21913)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812843bf)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128dc37)
Location: include/linux/page-flags.h:289
Inline: True
```
```
In mm/khugepaged.c (ffffffff81291ca9)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8129b7db)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8129f016)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_idle.c (ffffffff812a5ee5)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff81341a55)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff812252e8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f149)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81243ed0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8124d840)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff812581a5)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff81272e8a)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a9227b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a1222)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a85de)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812acbdf)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812b6969)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812ba6d2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_idle.c (ffffffff812c1641)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff81369e72)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff81233178)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d2d9)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81252390)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8125bd72)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81266675)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281cef)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ac9a0b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812affac)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b9abe)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812be4ad)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812c8839)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812cc5b2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff812d3571)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff81382092)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff812607b1)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265879)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81282842)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff81296bf9)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
```
In mm/page_alloc.c (ffffffff812b3fd6)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812e0de5)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e387e)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812ee678)
Location: include/linux/page-flags.h:328
Inline: True
```
```
In mm/khugepaged.c (ffffffff812f23cf)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memory-failure.c (ffffffff81301e13)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff8130923c)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813cc6c2)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff81268753)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81272205)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page_prepare
```
```
In mm/compaction.c (ffffffff8128c965)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff812bfa6a)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812ebbe5)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812eecee)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812f9ce8)
Location: include/linux/page-flags.h:336
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fe887)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memory-failure.c (ffffffff8130d875)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff81315090)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813de326)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff8126e4ed)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81277515)
Location: include/linux/page-flags.h:336
Inline: True
```
```
In mm/compaction.c (ffffffff81291868)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81296f33)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/page_alloc.c (ffffffff812c51ca)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81c2d7f6)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff812f4e7e)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8130049b)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff8130554a)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memory-failure.c (ffffffff81313d66)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8131b783)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff813e510a)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff812ab4f5)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b4ea5)
Location: include/linux/page-flags.h:350
Inline: True
```
```
In mm/compaction.c (ffffffff812d10fe)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff812d8303)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/page_alloc.c (ffffffff8130970a)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81d4c0e2)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff8133f47e)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
```
```
In mm/huge_memory.c (ffffffff8134a10d)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff8134f388)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memory-failure.c (ffffffff8135f046)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff81368a53)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff81436cda)
Location: include/linux/page-flags.h:350
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff813052e1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130d608)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81330871)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81338208)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813442ec)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/page_alloc.c (ffffffff8136b632)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81f1bad1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate_device.c (ffffffff813b67ee)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
```
```
In mm/huge_memory.c (ffffffff813c0b7b)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff813c5f2b)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memory-failure.c (ffffffff813da0f5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff813de33c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/page_idle.c (ffffffff813e65ae)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff814b1549)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/compaction.c (ffffffff813a7484)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff813af9ad)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/page_alloc.c (ffffffff813e7988)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff820c3ab8)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f4b47)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff81438052)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/huge_memory.c (ffffffff814429d8)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff8144aa79)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memory-failure.c (ffffffff81461a74)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff81464fcc)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/page_idle.c (ffffffff8146e09e)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8154812f)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/compaction.c (ffffffff813dacb9)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff813e41e1)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/page_alloc.c (ffffffff8141ca68)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8214795d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate_device.c (ffffffff8146dd22)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff81480b6f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memory-failure.c (ffffffff814972ae)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff8149aa94)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In fs/proc/page.c (ffffffff8157fd02)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/compaction.c (ffffffff81404bb3)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffffffff81449568)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8222a0ea)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate_device.c (ffffffff8149e6f2)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff814aeb4c)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
```
```
In mm/memory-failure.c (ffffffff814c87a9)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_isolation.c (ffffffff814ca17e)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In fs/proc/page.c (ffffffff815b86fa)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffff8000102c3320)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce690)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffff8000102eb00c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffff8000102f314c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffff8000102fd6e4)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffff80001031a434)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/migrate.c (ffff800010352ea0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffff80001035a254)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffff80001035fe1c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffff80001036b76c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffff80001037018c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffff8000103790f8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffff8000104501f8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (c04ecb18)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f84f8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (c050e5cc)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (c05154c4)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c051cabc)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (c053497c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memcontrol.c (c055ce28)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/page_idle.c (c0564670)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:320
Inline: True
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
In mm/swap.c (c00000000037d6d8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c518)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (c0000000003ac45c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (c0000000003b9b98)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c0000000003c897c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (c0000000003ed64c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (c0000000004309d4)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000435ff0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (c000000000443d30)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (c00000000044abb8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (c00000000045b2a0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (c000000000461d14)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (c00000000046bfec)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (c0000000005681f8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffe0001e2cda)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ec892)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffe0001ff4f4)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffe0002054ba)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffe00020bf8c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021fbc2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memcontrol.c (ffffffe000248e08)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/page_idle.c (ffffffe00025094a)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (0)
Location: include/linux/page-flags.h:320
Inline: True
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
In mm/swap.c (ffffffff8122b7c8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81235929)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff8124a9e0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff812543c2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125ecc5)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127a33f)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a6887b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a858c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b209e)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b6a8d)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812c0e19)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812c4b92)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff812cbb51)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8137a672)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff8121e8b8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81228993)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff8123d980)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81247012)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff812510f5)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126c22f)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81a2533b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff81299f4c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a342e)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812a7c5d)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812b1e6d)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812b5bd2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff812bc9d1)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8136b142)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff81229568)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812336c9)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81248780)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81252162)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125ca65)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff812780df)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ad4c8b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a639c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812afeae)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b489d)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812bec29)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812c29a2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff812c9961)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff81378142)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/swap.c (ffffffff81238978)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242c00)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/compaction.c (ffffffff81257fa5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81261b12)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8126c445)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/page_alloc.c (ffffffff81287ccf)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff81ae1166)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b66b7)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812c01ee)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/khugepaged.c (ffffffff812c528e)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812cf6a9)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812d3442)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_idle.c (ffffffff812da661)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/page.c (ffffffff8138bbf2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
