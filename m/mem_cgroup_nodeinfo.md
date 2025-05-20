# Function: <code>mem_cgroup_nodeinfo</code>

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
In mm/vmscan.c (ffffffff811bc695)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811d435b)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8121e16d)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
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
In mm/vmscan.c (ffffffff811ccd5a)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811e43ab)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81230760)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff811d59ec)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811ee80b)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8123bfaa)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/vmscan.c (ffffffff811eaf1d)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81204c7b)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8125b816)
Location: include/linux/memcontrol.h:297
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/page-writeback.c (ffffffff811fe75d)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8120c419)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8122566a)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8123e931)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812652ac)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff8127f326)
Location: include/linux/memcontrol.h:330
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/page-writeback.c (ffffffff8120f050)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8121f179)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81238a7e)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81252ec5)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81279fde)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff81293c06)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffff8121ebd1)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8122e94e)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81249dbe)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81265233)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129597c)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812af94d)
Location: include/linux/memcontrol.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffff8122c671)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8123cade)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125820e)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81273adb)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812a575c)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c44cf)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/filemap.c (ffffffff81250c77)
Location: include/linux/memcontrol.h:366
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
In mm/page-writeback.c (ffffffff81259f90)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8125fca1)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81269b62)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8126d463)
Location: include/linux/memcontrol.h:366
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
In mm/workingset.c (ffffffff812866ce)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/rmap.c (ffffffff812a5050)
Location: include/linux/memcontrol.h:366
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
In mm/slub.c (ffffffff812da387)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812e4a7d)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ea4a5)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f2002)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812fa3b4)
Location: include/linux/memcontrol.h:366
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
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
In mm/page-writeback.c (ffffffff81266882)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a3b7)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81274652)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/compaction.c (ffffffff8128cbfa)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81290a5e)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/slub.c (ffffffff812e6a79)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812ef461)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81301e55)
Location: include/linux/memcontrol.h:615
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
```
</details>
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
In mm/page-writeback.c (ffff8000102bbf80)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffff8000102cdd84)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffff8000102efdec)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffff800010309728)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffff8000103465ac)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010367118)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (c04e6fb0)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c04f7c58)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (c05136c4)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c0526228)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c054b1b4)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c05564d8)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_free_shrinker_maps
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
In mm/page-writeback.c (c00000000037388c)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c00000000038b984)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (c0000000003b48e0)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c0000000003d8dec)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c00000000042453c)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c000000000454580)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffe0001de1c6)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffe0001ec2b8)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffe000203814)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffe0002139ea)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffe000239474)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000242eea)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_free_shrinker_maps
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
In mm/page-writeback.c (ffffffff81224cc1)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8123512e)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125085e)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c12b)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129dd3c)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812bcaaf)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffff81217e63)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8122819e)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff812437de)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e19b)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8128f8cc)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812adc0f)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffff81222a61)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81232ece)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8124e5fe)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81269ecb)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129bb4c)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812ba8bf)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
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
In mm/page-writeback.c (ffffffff81231c41)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff812423de)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125df6e)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8127983b)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812aba31)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cafff)
Location: include/linux/memcontrol.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
</details>
</li>
</ul>

## Differences
