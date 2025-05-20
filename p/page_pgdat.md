# Function: <code>page_pgdat</code>

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
In mm/filemap.c (ffffffff811a20ab)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811b2a3d)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff811bc9f4)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff811c05c5)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811c6786)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff811d406f)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff811de866)
Location: include/linux/mm.h:936
Inline: True
```
```
In mm/rmap.c (ffffffff811e7eb1)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/migrate.c (ffffffff81213385)
Location: include/linux/mm.h:936
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/filemap.c (ffffffff811b1f15)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811c30bf)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff811cd0c7)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff811d0ba5)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811d5406)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff811e3f4a)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff811ee686)
Location: include/linux/mm.h:925
Inline: True
```
```
In mm/rmap.c (ffffffff811f9231)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/migrate.c (ffffffff812256ed)
Location: include/linux/mm.h:925
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/filemap.c (ffffffff811b8bd4)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c764e)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff811cb556)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff811d5d94)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff811d9145)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811de286)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff811ee53a)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff811f9626)
Location: include/linux/mm.h:967
Inline: True
```
```
In mm/rmap.c (ffffffff81203e1a)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8120bd88)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/slub.c (ffffffff8122666c)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81230deb)
Location: include/linux/mm.h:967
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/filemap.c (ffffffff811ca143)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811dc47d)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff811e09fc)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff811eb2b4)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff811ee425)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811f3d16)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff8120488a)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff81211a56)
Location: include/linux/mm.h:1018
Inline: True
```
```
In mm/rmap.c (ffffffff8121cb8a)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8122537b)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81236a00)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812416bc)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124eb49)
Location: include/linux/mm.h:1018
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
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
In mm/filemap.c (ffffffff811eb2d4)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811fe73c)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff812022ba)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8120cad7)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff8120ed61)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81215105)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff81225649)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff812327a2)
Location: include/linux/mm.h:1097
Inline: True
```
```
In mm/rmap.c (ffffffff8123e90e)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8124791e)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812599d0)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff8126528b)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81272985)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In fs/dcache.c (ffffffff812b73ab)
Location: include/linux/mm.h:1097
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_free_external_name
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
In mm/filemap.c (ffffffff811fbe44)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8120f02f)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81214c3c)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8121f946)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (ffffffff8122164c)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81227fe5)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff81238a5d)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff81245fe2)
Location: include/linux/mm.h:1165
Inline: True
```
```
In mm/rmap.c (ffffffff81252ea2)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8125bec3)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff8126d5e2)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81279fbd)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81286f1e)
Location: include/linux/mm.h:1165
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
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
In mm/filemap.c (ffffffff81213f46)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8121ebb0)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81223d99)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f0fd)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81230eb3)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81237c55)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/workingset.c (ffffffff8124a217)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff8124d8ba)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81258875)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff81265210)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff81277092)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81288b25)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81295968)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812a140b)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a238e)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812b694e)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812c1668)
Location: include/linux/mm.h:1233
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff81221756)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122c650)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81231b29)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d28d)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123f0b8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81245f05)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff8124eb6e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffffffff81258667)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff8125bdf1)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff81266d45)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff81273ab8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff81286b72)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81298695)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812a88d3)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812b282b)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b3738)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812c881e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812d3598)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff81250c59)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81259f72)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8125e6e9)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8126582d)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8126d445)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81274f25)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff8127ce2e)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff81282c64)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81286e7b)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81287d8c)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/memory.c (ffffffff81291b24)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81296f85)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff812a5032)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff812b96d6)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812cc20a)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812ddc34)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812e7dca)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812e9108)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f1fe4)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812fa38a)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff81309263)
Location: include/linux/mm.h:1421
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/page-writeback.c (ffffffff8126685c)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a8d2)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812701a7)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/vmstat.c (ffffffff81280035)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff8128d237)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8129115a)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81291989)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/mlock.c (ffffffff812a1a97)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swap_state.c (ffffffff812c48b2)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812d7a99)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812e6a56)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f31b6)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff812fc104)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81306291)
Location: include/linux/mm.h:1484
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
In mm/swap.c (ffffffff8126fa92)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275f9e)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/vmstat.c (ffffffff81284ab5)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff81291c87)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81296766)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812970d0)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/mlock.c (ffffffff812a7257)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swap_state.c (ffffffff812cb543)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812defb8)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812ee229)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f954f)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff813030d5)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130c75c)
Location: include/linux/mm.h:1540
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
In mm/swap.c (ffffffff812acd72)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b2618)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/vmstat.c (ffffffff812c35f5)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff812d1304)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6eda)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812d7a83)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/mlock.c (ffffffff812e876f)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/swap_state.c (ffffffff813105df)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81326c48)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81336769)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff81343751)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8134ce45)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8135795c)
Location: include/linux/mm.h:1551
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
In mm/filemap.c (ffffffff812f01fb)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813007ca)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81306e84)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff8130f3fe)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff81320995)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff81330af7)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81336704)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81337ca8)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff8134a94f)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/swap_state.c (ffffffff8137b17d)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff813962af)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff813a80dc)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff813b5ee2)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff813c445d)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d06f2)
Location: include/linux/mm.h:1486
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8136b108)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f6a0)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff8137e716)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff81393ff5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff813a7968)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad972)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae97e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff813c353f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/swap_state.c (ffffffff813f8be5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff814162b4)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff8142c151)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff8143607c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8144854c)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81455dcb)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8139d267)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a17c0)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813afe00)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff813c7275)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff813daf3b)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1e62)
Location: include/linux/mm.h:1812
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
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff813f8afe)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/swap_state.c (ffffffff8142b9a1)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81449551)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/slub.c (ffffffff814616d7)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff8146be89)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:putback_movable_pages
```
```
In mm/khugepaged.c (ffffffff8147ddf7)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff8148ce65)
Location: include/linux/mm.h:1812
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
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
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813c6f1d)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb441)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
```
```
In mm/vmscan.c (ffffffff813d92ed)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff813f1505)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (ffffffff814050c9)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c68f)
Location: include/linux/mm.h:1867
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
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mlock.c (ffffffff814246bb)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/slub.c (ffffffff8145976f)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/swap_state.c (ffffffff814650f9)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/zswap.c (ffffffff8147059d)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/mempolicy.c (ffffffff81482fa8)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
```
```
In mm/migrate.c (ffffffff8149ad99)
Location: include/linux/mm.h:1867
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
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814bc7a2)
Location: include/linux/mm.h:1867
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__lruvec_stat_mod_folio
```
```
In mm/memory-failure.c (ffffffff814c66d7)
Location: include/linux/mm.h:1867
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102aed60)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bbf60)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffff8000102c17cc)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce61c)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d1754)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffff8000102db3a4)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffff8000102e4e34)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffff8000102f048c)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffff8000102f3194)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffff8000102fdf50)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffff800010309708)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffff8000103213f8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffff8000103372c0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffff80001034a2e0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffff800010353184)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff80001035485c)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffff80001036b740)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffff800010379150)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (c04da970)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c04e6f98)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (c04ecb34)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f8498)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c04f8b70)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c050241c)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (c0509cec)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (c0513b54)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (c0515514)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c051cae4)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/rmap.c (c0526210)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (c0539c88)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/slub.c (c054ec10)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c0552ab0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (c055ce20)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:1247
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
In mm/filemap.c (c0000000003621dc)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c000000000373868)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (c00000000037b5a4)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c4a4)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c00000000038f1c0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c00000000039c19c)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (c0000000003a6a04)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (c0000000003b4ee0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (c0000000003b9bf4)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (c0000000003c95bc)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (c0000000003d8dc8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (c0000000003f6974)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (c000000000411ca4)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (c0000000004291ac)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c000000000439da0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c00000000043b7dc)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (c00000000045b270)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (c00000000046c040)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1247
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:1247
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
In mm/filemap.c (ffffffff81219da6)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81224ca0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8122a179)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812358dd)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81237708)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8123e555)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff812471be)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffffffff81250cb7)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81254441)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125f395)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff8126c108)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8127f1c2)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff81290c75)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812a0eb3)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812aae0b)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812abd18)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812c0dfe)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812cbb78)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff8120cfb6)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81217e42)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8121d299)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122894d)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122a598)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81231555)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff8123a16e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffffffff81243bf7)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81247091)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff812517b5)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff8125e178)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff81270fe2)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff812828f5)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81292993)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff8129c73f)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8129d888)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812b1e52)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812bc9f8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff81217b46)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81222a40)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81227f19)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123367d)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812354a8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8123c2f5)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff81244f5e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffffffff8124ea57)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812521e1)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8125d135)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff81269ea8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8127cf62)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff8128ea85)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff8129ecc3)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812a8c1b)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a9b28)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812bec0e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812c9988)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
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
In mm/filemap.c (ffffffff81226c06)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81231c20)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81237259)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242bbd)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812455b8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8124ba55)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/slab_common.c (ffffffff8125494e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/workingset.c (ffffffff8125e3d0)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81261b91)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/mlock.c (ffffffff8126cb35)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff81279818)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/swap_state.c (ffffffff8128cb22)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/mempolicy.c (ffffffff8129e985)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812aedcf)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812b8f39)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b9da8)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memcontrol.c (ffffffff812cf68e)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/page_idle.c (ffffffff812da688)
Location: include/linux/mm.h:1247
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
</details>
</li>
</ul>

## Differences
