# Function: <code>node_lruvec</code>

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
In mm/page_alloc.c (ffffffff81897901)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/vmscan.c (ffffffff811bc445)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811d4377)
Location: include/linux/mmzone.h:743
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
In mm/page_alloc.c (ffffffff818cc054)
Location: include/linux/mmzone.h:717
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/vmscan.c (ffffffff811ccb0a)
Location: include/linux/mmzone.h:717
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811e43c7)
Location: include/linux/mmzone.h:717
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81232b07)
Location: include/linux/mmzone.h:717
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
In mm/page_alloc.c (ffffffff819035ce)
Location: include/linux/mmzone.h:737
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/vmscan.c (ffffffff811d57e9)
Location: include/linux/mmzone.h:737
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff811ee82a)
Location: include/linux/mmzone.h:737
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8123e324)
Location: include/linux/mmzone.h:737
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
In mm/page_alloc.c (ffffffff8198d4de)
Location: include/linux/mmzone.h:741
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/vmscan.c (ffffffff811eabe3)
Location: include/linux/mmzone.h:741
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81204c9a)
Location: include/linux/mmzone.h:741
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8125dec4)
Location: include/linux/mmzone.h:741
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
In mm/page_alloc.c (ffffffff819e9da1)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/page-writeback.c (ffffffff811fe858)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8120c462)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8122579e)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8123e9f5)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812653c1)
Location: include/linux/mmzone.h:743
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff8128214b)
Location: include/linux/mmzone.h:743
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
In mm/page_alloc.c (ffffffff81a24e0a)
Location: include/linux/mmzone.h:736
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/page-writeback.c (ffffffff8120f112)
Location: include/linux/mmzone.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8121f1c2)
Location: include/linux/mmzone.h:736
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81238ca4)
Location: include/linux/mmzone.h:736
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
In mm/rmap.c (ffffffff81252f89)
Location: include/linux/mmzone.h:736
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8127a0f3)
Location: include/linux/mmzone.h:736
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff8129632b)
Location: include/linux/mmzone.h:736
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
In mm/page-writeback.c (ffffffff8121ec1b)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8122e994)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff81249f3a)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff812652c6)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81a95241)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff81295a11)
Location: include/linux/mmzone.h:788
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812adcaa)
Location: include/linux/mmzone.h:788
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
In mm/page-writeback.c (ffffffff8122c6bb)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8123cb24)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125838a)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81273b6f)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81accb24)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff812a57f1)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c45f1)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (ffff8000102bc13c)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffff8000102cdfa4)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffff8000102eff84)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffff80001030978c)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffff800010d9fa68)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffff800010346654)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036724c)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/vmscan.c (c04f7c50)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/page_alloc.c (c1531ab0)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
```
In mm/slub.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (c0000000003738e0)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c00000000038bc40)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (c0000000003b4af0)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (c0000000003d8e70)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (c000000000eec3bc)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (c000000000424630)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c000000000454690)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/vmscan.c (ffffffe0001ec062)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/mmzone.h:795
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (ffffffff81224d0b)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81235174)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff812509da)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8126c1bf)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81a6b994)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff8129ddd1)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812bcbd1)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (ffffffff81217ea5)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff812281e4)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8124395a)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff8125e22f)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81a27edb)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff8128f94d)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812add25)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (ffffffff81222aab)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81232f14)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8124e77a)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff81269f5f)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81ad7da4)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff8129bbe1)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812ba9e1)
Location: include/linux/mmzone.h:795
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
In mm/page-writeback.c (ffffffff81231c8b)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81242424)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/workingset.c (ffffffff8125e0ea)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/rmap.c (ffffffff812798cf)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81ae4264)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/page_alloc.c:pgdat_init_internals
```
```
In mm/slub.c (ffffffff812abadf)
Location: include/linux/mmzone.h:795
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cb121)
Location: include/linux/mmzone.h:795
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
