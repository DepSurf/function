# Function: <code>folio_pgdat</code>

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
In mm/filemap.c (ffffffff812f01fb)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813007ca)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81306e84)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3fe)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/compaction.c (ffffffff81330af7)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81336704)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81337ca8)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff8134a94f)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/slub.c (ffffffff813a80dc)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d06f2)
Location: include/linux/mm.h:1496
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
In mm/filemap.c (ffffffff8135b59b)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8136b108)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f6a0)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff8137e716)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/compaction.c (ffffffff813a7968)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad972)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae97e)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff813c353f)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/swap_state.c (ffffffff813f8be5)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/slub.c (ffffffff8142c151)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff81434fad)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/memcontrol.c (ffffffff81455dcb)
Location: include/linux/mm.h:1609
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
In mm/filemap.c (ffffffff8138d3fb)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8139d267)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a17c0)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813afe00)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/compaction.c (ffffffff813daf3b)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1e62)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813e327e)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff813f8afe)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/swap_state.c (ffffffff8142b9a1)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81449551)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/slub.c (ffffffff814616d7)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff81468009)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8147b2a7)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff8148ce65)
Location: include/linux/mm.h:1822
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
In mm/filemap.c (ffffffff813b6f77)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813c6f1d)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb441)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813d92ed)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/compaction.c (ffffffff814050c9)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c68f)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff8140db09)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff814246bb)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/slub.c (ffffffff8145976f)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/swap_state.c (ffffffff814650f9)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/zswap.c (ffffffff8147059d)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/mempolicy.c (ffffffff81482fa8)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8149ad99)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff814ad096)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814bc7a2)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__lruvec_stat_mod_folio
```
```
In mm/memory-failure.c (ffffffff814c66d7)
Location: include/linux/mm.h:1877
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
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
