# Function: <code>count_vm_events</code>

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
In mm/vmscan.c (ffffffff811a0759)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811ad67e)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff811b585b)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2ff7)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff811c8ac4)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff811e1342)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff811f286a)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-core.c (ffffffff813b9d9e)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff811b97e9)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811c6835)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff811cfdcb)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff811ded1d)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff811e4d06)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff811ffd32)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812133de)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff813fdb80)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff811c9e3f)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811d69c5)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff811dfdf3)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff811eeb3d)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff811f4d35)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff81211852)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff81225746)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814174b9)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff811d28ea)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811df825)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff811eb956)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff811f9af1)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff811ffb80)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mempolicy.c (ffffffff8121d172)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff81230dd3)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff81425319)
Location: include/linux/vmstat.h:48
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff811e7df8)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff811f5645)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff81201cd2)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81211f50)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812183f0)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff81224a2c)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff81238362)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8124eb31)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814503e9)
Location: include/linux/vmstat.h:59
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff812092d4)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/vmstat.c (ffffffff812168b5)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff81223098)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81232c80)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff81239db7)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/page_io.c (ffffffff81246eb5)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff8125b8e2)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8127296d)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814836fd)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff8121bfb4)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff812297c5)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff812360eb)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81246452)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff8124d988)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff8125b2e8)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff81270192)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff81286f06)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff8149eebd)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff8122bbb8)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81239472)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff812475cf)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81258686)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff8125fee2)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff81276436)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff8128b7a3)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812a13f3)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814ccf9a)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff81239a7a)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81247782)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff81255a3c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81266b56)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff8126e788)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff81285f26)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff8129b313)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812b2813)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814e61e6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff81266351)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81275969)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff812841a6)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff81296de0)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff8129ed87)
Location: include/linux/vmstat.h:78
Inline: True
```
```
In mm/page_io.c (ffffffff812b8242)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff812ce6a5)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812e7db2)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff8154546c)
Location: include/linux/vmstat.h:78
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/swap.c (ffffffff8126aa7e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff8127048e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81280249)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff8128e33a)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff812a1bde)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812aa150)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff812c390c)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff812d9635)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812f319e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff81561acc)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/swap.c (ffffffff8126fc5e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff81276347)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81285359)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff812939c9)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff812a745f)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812af5cf)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff812ca6d8)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff812e0eb5)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812f9537)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff8156a22c)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/swap.c (ffffffff812acf35)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff812b29c8)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff812c3be9)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff812d3dd2)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff812e8a9f)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812f0dfe)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff8130f6d5)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff81328185)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8134385c)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff815cd9af)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/swap.c (ffffffff813046d5)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f89d)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81321009)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff81332ca0)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mprotect.c (ffffffff81354722)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff81379131)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/mempolicy.c (ffffffff8139739e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff813b60a8)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff8167994d)
Location: include/linux/vmstat.h:79
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
In mm/swap.c (ffffffff8136d860)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137ea83)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81394f79)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff813a99d8)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mprotect.c (ffffffff813cec44)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff813f6ae2)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/mempolicy.c (ffffffff81416f6e)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff81436200)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff81735dd7)
Location: include/linux/vmstat.h:79
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
In mm/swap.c (ffffffff8139fa92)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813b016a)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff813c7af1)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff813dcc83)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mprotect.c (ffffffff8140352a)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff81429972)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/mempolicy.c (ffffffff8144a4f6)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8146bec2)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff817723ba)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/swap.c (ffffffff813c96ee)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d9652)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shrinker.c (ffffffff813e3fbc)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff813f24d1)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff81406bd8)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mprotect.c (ffffffff8142faba)
Location: include/linux/vmstat.h:79
Inline: True
```
```
In mm/page_io.c (ffffffff814633cb)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/page_io.c:sio_read_complete
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/mempolicy.c (ffffffff81483f76)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8149ae92)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff817b4767)
Location: include/linux/vmstat.h:79
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffff8000102ca94c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffff8000102dbb6c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffff8000102ecf74)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffff8000102fdafc)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffff800010305504)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffff8000103204c8)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffff80001033a17c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffff80001035313c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffff8000105e37c4)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (c04f4810)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (c0501c98)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (c0510e58)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (c051cf44)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/page_io.c (c0538f14)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (c0552b64)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (c0790ab4)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (c000000000387578)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (c00000000039b644)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (c0000000003b0b38)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (c0000000003c904c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (c0000000003d2a30)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (c0000000003f5620)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (c000000000414800)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (c000000000439d44)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (c00000000077718c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffe0001e99ce)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffe0001f4cec)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffe000201608)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffe00020c2f0)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/page_io.c (ffffffe000221ba8)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (ffffffe00023fb86)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffe000425234)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff812320ca)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff8123fdd2)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff8124e08c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff8125f1a6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff81266dd8)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff8127e576)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff812938f3)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812aadf3)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814de7c6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff8122518a)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff81232dd2)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff8124102c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff812515d0)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff81258fff)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff812703a6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff81285503)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff8129c727)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814cf166)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff8122fe6a)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff8123db72)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff8124be2c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff8125cf46)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff81264b78)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff8127c316)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff81291703)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812a8c03)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814da856)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
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
In mm/vmscan.c (ffffffff8123f2b3)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmstat.c (ffffffff8124d2a2)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:vm_events_fold_cpu
```
```
In mm/compaction.c (ffffffff8125b73c)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/mlock.c (ffffffff8126c8b6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff81274550)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_io.c (ffffffff8128bee6)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/mempolicy.c (ffffffff812a1513)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/mempolicy.c:change_prot_numa
```
```
In mm/migrate.c (ffffffff812b8f21)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In block/blk-core.c (ffffffff814f3556)
Location: include/linux/vmstat.h:70
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
</details>
</li>
</ul>

## Differences
