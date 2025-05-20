# Function: <code>mem_cgroup_lruvec</code>

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
In mm/vmscan.c (ffffffff811bc445)
Location: include/linux/memcontrol.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811d4356)
Location: include/linux/memcontrol.h:328
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
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
In mm/vmscan.c (ffffffff811ccb0a)
Location: include/linux/memcontrol.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811e43a6)
Location: include/linux/memcontrol.h:328
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81232ab4)
Location: include/linux/memcontrol.h:328
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff811d57e9)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811ee806)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8123e2c4)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
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
In mm/vmscan.c (ffffffff811eabe3)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81204c76)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8125de64)
Location: include/linux/memcontrol.h:311
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff811fe758)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8120c414)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81225665)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8123e92c)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812652a7)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff812820f1)
Location: include/linux/memcontrol.h:344
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8120f04b)
Location: include/linux/memcontrol.h:369
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8121f174)
Location: include/linux/memcontrol.h:369
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81238a79)
Location: include/linux/memcontrol.h:369
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
In mm/rmap.c (ffffffff81252ec0)
Location: include/linux/memcontrol.h:369
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81279fd9)
Location: include/linux/memcontrol.h:369
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff812962d1)
Location: include/linux/memcontrol.h:369
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/page-writeback.c (ffffffff8121ebcc)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8122e949)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81249db9)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126522e)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81295977)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812adbf1)
Location: include/linux/memcontrol.h:371
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff8122c66c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8123cad9)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81258209)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81273ad6)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812a5757)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c44ca)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/filemap.c (ffffffff81250c72)
Location: include/linux/memcontrol.h:379
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
In mm/page-writeback.c (ffffffff81259f8b)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8125fc9c)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81269b5d)
Location: include/linux/memcontrol.h:379
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
In mm/shmem.c (ffffffff8126d45e)
Location: include/linux/memcontrol.h:379
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
In mm/workingset.c (ffffffff812866c9)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/rmap.c (ffffffff812a504b)
Location: include/linux/memcontrol.h:379
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
In mm/slub.c (ffffffff812da374)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812e4a63)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ea4a0)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f1ffd)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812fa39a)
Location: include/linux/memcontrol.h:379
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff8126686c)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a3a2)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff8127464d)
Location: include/linux/memcontrol.h:629
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
In mm/compaction.c (ffffffff8128cbdd)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81290a59)
Location: include/linux/memcontrol.h:629
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
In mm/slub.c (ffffffff812e6a62)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812ef447)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81301e3b)
Location: include/linux/memcontrol.h:629
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff8126f4b7)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81279680)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/compaction.c (ffffffff81291a49)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81295f9c)
Location: include/linux/memcontrol.h:716
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
In mm/slub.c (ffffffff812ee235)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f60c2)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff813081d6)
Location: include/linux/memcontrol.h:716
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
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
In mm/swap.c (ffffffff812ac607)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff812b74f8)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/compaction.c (ffffffff812d1320)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d664c)
Location: include/linux/memcontrol.h:729
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
In mm/migrate.c (ffffffff813406b6)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff813539c7)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
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
In mm/swap.c (ffffffff81306761)
Location: include/linux/memcontrol.h:730
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff8131225e)
Location: include/linux/memcontrol.h:730
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/compaction.c (ffffffff81330b06)
Location: include/linux/memcontrol.h:730
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81335e9c)
Location: include/linux/memcontrol.h:730
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
In mm/migrate.c (ffffffff813b2017)
Location: include/linux/memcontrol.h:730
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff813cba09)
Location: include/linux/memcontrol.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
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
In mm/swap.c (ffffffff81370821)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81385672)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:prepare_scan_count
```
```
In mm/compaction.c (ffffffff813a7977)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad0dc)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/migrate.c (ffffffff81431b52)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff81450711)
Location: include/linux/memcontrol.h:712
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
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
In mm/swap.c (ffffffff813a29d1)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813b8b0e)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:prepare_scan_count
```
```
In mm/compaction.c (ffffffff813daf4a)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e14cc)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/migrate.c (ffffffff81467774)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff81486171)
Location: include/linux/memcontrol.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
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
In mm/swap.c (ffffffff813cc64e)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813e1b0e)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:prepare_scan_control
```
```
In mm/compaction.c (ffffffff814050d8)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140bd9d)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/zswap.c (ffffffff814703be)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_shrinker_count
  - mm/zswap.c:zswap_shrinker_scan
  - mm/zswap.c:zswap_lru_add
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/migrate.c (ffffffff81496a12)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/memcontrol.c (ffffffff814b5990)
Location: include/linux/memcontrol.h:738
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__lruvec_stat_mod_folio
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
In mm/page-writeback.c (ffff8000102bbf7c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffff8000102cdd80)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffff8000102efde8)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffff800010309724)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffff8000103465a8)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff800010367114)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (c04e6fa4)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c04f7c40)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (c05136b0)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c052621c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c054b1a8)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c05585a8)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (c000000000373888)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c00000000038b980)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (c0000000003b48dc)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c0000000003d8de8)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c000000000424538)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045457c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffe0001de1ba)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffe0001ec062)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffe000203800)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffe0002139de)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffe000239468)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000245090)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff81224cbc)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81235129)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81250859)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c126)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129dd37)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812bcaaa)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff81217e5e)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81228199)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff812437d9)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e196)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8128f8c7)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812adc0a)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff81222a5c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81232ec9)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8124e5f9)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81269ec6)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129bb47)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812ba8ba)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
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
In mm/page-writeback.c (ffffffff81231c3c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff812423d9)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125df69)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81279836)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812aba2c)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812caffa)
Location: include/linux/memcontrol.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
</details>
</li>
</ul>

## Differences
