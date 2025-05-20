# Function: <code>__folio_objcg</code>

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
In mm/page-writeback.c (ffffffff812ff3c6)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81306eb7)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f925)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/compaction.c (ffffffff81330af3)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81336700)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/mlock.c (ffffffff8134af21)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/vmalloc.c (ffffffff81366bf1)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_io.c (ffffffff81379ad3)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (ffffffff813b2002)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813c16ab)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c4b74)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813d5ae7)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:folio_memcg_unlock
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In fs/fs-writeback.c (ffffffff8143123b)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff814444f0)
Location: include/linux/memcontrol.h:420
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
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
In mm/page-writeback.c (ffffffff813679fa)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f912)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff8137ea41)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff813a7964)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad96e)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/mlock.c (ffffffff813c3b52)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/vmalloc.c (ffffffff813e297c)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_io.c (ffffffff813f78ad)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (ffffffff81431b3d)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff8144375d)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81447fa9)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8145b513)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:folio_memcg_unlock
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_page
```
```
In fs/fs-writeback.c (ffffffff814befc8)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff814d3760)
Location: include/linux/memcontrol.h:396
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
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
In mm/page-writeback.c (ffffffff81399e9a)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a1a32)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813b0128)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff813daf37)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1e5e)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/mlock.c (ffffffff813f8ddb)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/vmalloc.c (ffffffff8141754e)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
```
In mm/page_io.c (ffffffff81429c68)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/page_io.c:bio_associate_blkg_from_page
```
```
In mm/migrate.c (ffffffff8146775f)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81478e78)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147d959)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff81491183)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:folio_memcg_unlock
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_css_from_folio
```
```
In fs/fs-writeback.c (ffffffff814f40e0)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff81509d2c)
Location: include/linux/memcontrol.h:402
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
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
In mm/page-writeback.c (ffffffff813c3b57)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb6bd)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813d9610)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/compaction.c (ffffffff814054ad)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c68b)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/mlock.c (ffffffff81424993)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/vmalloc.c (ffffffff8144405e)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_io.c (ffffffff814642bd)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage
```
```
In mm/zswap.c (ffffffff81470599)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/migrate.c (ffffffff814969f9)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a8458)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:folio_undo_large_rmappable
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814abcaa)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff814c0af3)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:folio_memcg_unlock
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__lruvec_stat_mod_folio
  - mm/memcontrol.c:mem_cgroup_css_from_folio
```
```
In fs/fs-writeback.c (ffffffff815287f0)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - fs/fs-writeback.c:perf_trace_track_foreign_dirty
  - fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty
```
```
In fs/buffer.c (ffffffff8153eb4d)
Location: include/linux/memcontrol.h:406
Inline: True
Inline callers:
  - fs/buffer.c:folio_alloc_buffers
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
