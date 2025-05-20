# Function: <code>__page_objcg</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126aef1)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8126fab6)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81276333)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff81291a45)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81296785)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/mlock.c (ffffffff812a727d)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/page_io.c (ffffffff812ca685)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (ffffffff812f60a7)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81300c02)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8130470b)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81310ef6)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In fs/fs-writeback.c (ffffffff8135c5a3)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff8136e65d)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
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
In mm/page-writeback.c (ffffffff812a4b8e)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff812acda3)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b29fb)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff812d131c)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6ef2)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/mlock.c (ffffffff812e8b8e)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/page_io.c (ffffffff8130f682)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (ffffffff8134069f)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134a8a2)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134e440)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8135c1f1)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In fs/fs-writeback.c (ffffffff813aaa43)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff813bd8f0)
Location: include/linux/memcontrol.h:418
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
</details>
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
