# Function: <code>mem_cgroup_disabled</code>

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
In mm/filemap.c (ffffffff8118fadd)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff811a04b9)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:mem_cgroup_shrink_node_zone
```
```
In mm/shmem.c (ffffffff811aae12)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff811bec1d)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff811f95b9)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_zone_lruvec
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_replace_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In fs/dax.c (ffffffff8125ddf2)
Location: include/linux/memcontrol.h:350
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
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
In mm/filemap.c (ffffffff811a3a43)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff811bc690)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
```
```
In mm/shmem.c (ffffffff811c0f6c)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff811d433d)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811daa85)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/memcontrol.c (ffffffff812245c6)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In fs/dax.c (ffffffff81287ec8)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
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
In mm/filemap.c (ffffffff811b3d9f)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/vmscan.c (ffffffff811ccd55)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff811d156b)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff811e438d)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811ea5f9)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/memcontrol.c (ffffffff81236b96)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_get_limit
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
```
In fs/dax.c (ffffffff8129c825)
Location: include/linux/memcontrol.h:280
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In kernel/fork.c (ffffffff810812e2)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (ffffffff811ba8bc)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811bd476)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff811c766c)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff811ca724)
Location: include/linux/memcontrol.h:270
Inline: True
```
```
In mm/vmscan.c (ffffffff811d59e7)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff811d9dc9)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff811ee54e)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811f495b)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81203e37)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81226691)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff81242657)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_get_limit
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
```
In fs/dax.c (ffffffff812ab908)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In kernel/fork.c (ffffffff81087bd2)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (ffffffff811ce077)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811d209b)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff811dc49b)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff811df659)
Location: include/linux/memcontrol.h:270
Inline: True
```
```
In mm/vmscan.c (ffffffff811eaf18)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff811efaae)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff8120489e)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8120c7b8)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8121cba7)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812416de)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff81262497)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_get_limit
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
```
In fs/dax.c (ffffffff812cf255)
Location: include/linux/memcontrol.h:270
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In kernel/fork.c (ffffffff8108af53)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (ffffffff811efbff)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811f3ca0)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (ffffffff811fe758)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81200e17)
Location: include/linux/memcontrol.h:309
Inline: True
```
```
In mm/vmscan.c (ffffffff8120c414)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff81211251)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff81225665)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff812302a1)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8123e92c)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812652a7)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff82709f05)
Location: include/linux/memcontrol.h:309
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/dax.c (ffffffff812f9a99)
Location: include/linux/memcontrol.h:309
Inline: True
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
In kernel/fork.c (ffffffff81093620)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (ffffffff81201e5a)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81204933)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8120f04b)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8121378c)
Location: include/linux/memcontrol.h:331
Inline: True
```
```
In mm/vmscan.c (ffffffff8121f174)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff8122319e)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/workingset.c (ffffffff81238a79)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81242c51)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81252ec0)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81279fd9)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memcontrol.c (ffffffff828c1244)
Location: include/linux/memcontrol.h:331
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/dax.c (ffffffff8130da44)
Location: include/linux/memcontrol.h:331
Inline: True
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
In mm/filemap.c (ffffffff81217c8a)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8121c0a6)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8121ebcc)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8122e949)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff812331c1)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff81249db9)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81254af6)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8126522e)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff81295977)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828da5c5)
Location: include/linux/memcontrol.h:333
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff81335c71)
Location: include/linux/memcontrol.h:333
Inline: True
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
In mm/filemap.c (ffffffff8122555e)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81229a38)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8122c66c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff8123cad9)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff812413e2)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff81258209)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81263056)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81273ad6)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812a5757)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828e2a6c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff81349871)
Location: include/linux/memcontrol.h:354
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool mem_cgroup_disabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253534)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/oom_kill.c (ffffffff8125688b)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81259f8b)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8125f991)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81269b5d)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff8126dc3d)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/workingset.c (ffffffff812866c9)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff81294e32)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812a504b)
Location: include/linux/memcontrol.h:337
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
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812e4a63)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ea4a0)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f1ffd)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812fe028)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:mod_memcg_obj_state
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_lruvec_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
```
```
In fs/dax.c (ffffffff8138eae6)
Location: include/linux/memcontrol.h:337
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812fe36a-ffffffff812fe375: mem_cgroup_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool mem_cgroup_disabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258820)
Location: include/linux/memcontrol.h:521
Inline: True
```
```
In mm/oom_kill.c (ffffffff81261422)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8126686c)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8126a8e1)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812701b6)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff81276490)
Location: include/linux/memcontrol.h:521
Inline: True
```
```
In mm/compaction.c (ffffffff8128cbdd)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81290a59)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff8129f6b6)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff812a1aa6)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/slub.c (ffffffff812e6a62)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812ef447)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f4b10)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff8130a4b8)
Location: include/linux/memcontrol.h:521
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_lruvec_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
```
```
In fs/dax.c (ffffffff8139df20)
Location: include/linux/memcontrol.h:521
Inline: True
```
**Symbols:**

```
ffffffff813001e0-ffffffff813001ee: mem_cgroup_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool mem_cgroup_disabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ce80)
Location: include/linux/memcontrol.h:611
Inline: True
```
```
In mm/oom_kill.c (ffffffff81265c5e)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff8126aedb)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8126faa1)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275fad)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:prealloc_shrinker
```
```
In mm/shmem.c (ffffffff8127d0c0)
Location: include/linux/memcontrol.h:611
Inline: True
```
```
In mm/compaction.c (ffffffff81291a49)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81295f9c)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812a46b6)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff812a7267)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/slub.c (ffffffff812ee235)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f60c2)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812fb091)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff81310d58)
Location: include/linux/memcontrol.h:611
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_lruvec_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
```
```
In fs/dax.c (ffffffff813a6c60)
Location: include/linux/memcontrol.h:611
Inline: True
```
**Symbols:**

```
ffffffff81306f40-ffffffff81306f4e: mem_cgroup_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool mem_cgroup_disabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290c23)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129c183)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/oom_kill.c (ffffffff812a248e)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812a4b7b)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff812acd8a)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b29e3)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:prealloc_shrinker
```
```
In mm/shmem.c (ffffffff812ba4e2)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff812d1320)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d664c)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812e5969)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e8b75)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/page_alloc.c (ffffffff813056d5)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swapfile.c (ffffffff81313f08)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff813186c7)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/ksm.c (ffffffff81331f51)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff813406b6)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81344efa)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e419)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8135be98)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
```
```
In mm/vmpressure.c (ffffffff8135c3d5)
Location: include/linux/memcontrol.h:602
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135ecb9)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/userfaultfd.c (ffffffff8136704f)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff81369ed6)
Location: include/linux/memcontrol.h:602
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
```
```
In fs/dax.c (ffffffff813f6b20)
Location: include/linux/memcontrol.h:602
Inline: True
```
**Symbols:**

```
ffffffff81350c00-ffffffff81350c0b: mem_cgroup_disabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool mem_cgroup_disabled();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5eb1)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f48fa)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/oom_kill.c (ffffffff812f9fca)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff812ff378)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81306e9c)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff8130f8fb)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:prealloc_shrinker
```
```
In mm/shmem.c (ffffffff813187bc)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81330b06)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81335e9c)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff81347c79)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff8134af09)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/vmalloc.c (ffffffff81366bbd)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff8136d9e0)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swapfile.c (ffffffff8137f5d3)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81383d75)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/ksm.c (ffffffff813a3171)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff813b2017)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff813b7deb)
Location: include/linux/memcontrol.h:582
Inline: True
```
```
In mm/huge_memory.c (ffffffff813ba202)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c4b38)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813d57ad)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
```
```
In mm/vmpressure.c (ffffffff813d5ff5)
Location: include/linux/memcontrol.h:582
Inline: True
```
```
In mm/memory-failure.c (ffffffff813d92d3)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/userfaultfd.c (ffffffff813e45ce)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff813e7c13)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dax.c (ffffffff8146a155)
Location: include/linux/memcontrol.h:582
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813c90d0-ffffffff813c90e3: mem_cgroup_disabled (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff8134fb0e)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e8ff)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/oom_kill.c (ffffffff813646fa)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813679e9)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f8f9)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__folio_put
```
```
In mm/vmscan.c (ffffffff8137ea26)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:should_run_aging
  - mm/vmscan.c:should_run_aging
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:iterate_mm_list
  - mm/vmscan.c:iterate_mm_list
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:__prealloc_shrinker
```
```
In mm/shmem.c (ffffffff8138c569)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff813a7977)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad0dc)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813c0069)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813c3b3a)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/vmalloc.c (ffffffff813e294a)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/page_alloc.c (ffffffff813e9e60)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swapfile.c (ffffffff813fe113)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff8140172e)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/ksm.c (ffffffff81422dea)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81431b52)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff81439ac2)
Location: include/linux/memcontrol.h:560
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c357)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814495e9)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff83ec7135)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:lock_page_memcg
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
```
```
In mm/vmpressure.c (ffffffff8145ba25)
Location: include/linux/memcontrol.h:560
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8145c385)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/memory-failure.c (ffffffff8145f593)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/userfaultfd.c (ffffffff8146c2a7)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff8146fa4d)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dax.c (ffffffff814fabf2)
Location: include/linux/memcontrol.h:560
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In kernel/events/uprobes.c (ffffffff81380ccd)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813917f7)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/oom_kill.c (ffffffff81396bcd)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81399e89)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a1a19)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__folio_put
```
```
In mm/vmscan.c (ffffffff813b010d)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:prepare_scan_count
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:__prealloc_shrinker
```
```
In mm/shmem.c (ffffffff813beb95)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff813daf4a)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e14cc)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813f4d6f)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813f8dc3)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/vmalloc.c (ffffffff8141751b)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
```
In mm/page_alloc.c (ffffffff8141ee90)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swapfile.c (ffffffff814310f3)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff8143460e)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/ksm.c (ffffffff81457f69)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81467774)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8146e7f0)
Location: include/linux/memcontrol.h:573
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147172f)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147d89f)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff836ec125)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:__mod_lruvec_state
```
```
In mm/vmpressure.c (ffffffff814916a5)
Location: include/linux/memcontrol.h:573
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff81492025)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/memory-failure.c (ffffffff814957ae)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/userfaultfd.c (ffffffff814a1131)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/memremap.c (ffffffff814a422d)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dax.c (ffffffff81532045)
Location: include/linux/memcontrol.h:573
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In kernel/events/uprobes.c (ffffffff813aa096)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813bb57e)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/oom_kill.c (ffffffff813c093d)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff813c3b46)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb6a4)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:lru_note_cost
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__folio_put
```
```
In mm/vmscan.c (ffffffff813d95f5)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:lru_gen_shrink_node
  - mm/vmscan.c:shrink_many
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:lruvec_is_sizable
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_swappiness
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:prepare_scan_control
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:inactive_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shrinker.c (ffffffff813e43f3)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_alloc
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/shmem.c (ffffffff813ed9ed)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff814050d8)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140bd9d)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff814213df)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff8142497b)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/vmalloc.c (ffffffff8144402b)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144bb76)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/page_alloc.c:destroy_large_folio
```
```
In mm/swapfile.c (ffffffff8146a513)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/swap_slots.c (ffffffff8146da08)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff8146f17a)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_shrinker_count
  - mm/zswap.c:zswap_shrinker_scan
  - mm/zswap.c:zswap_lru_add
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/hugetlb.c (ffffffff81476f46)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_folio
```
```
In mm/ksm.c (ffffffff814928d4)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81496a12)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8149d249)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a2110)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814abc46)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8391f125)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_hugetlb_try_charge
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__lruvec_stat_mod_folio
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
```
```
In mm/vmpressure.c (ffffffff814c1085)
Location: include/linux/memcontrol.h:577
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff814c1a35)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/memory-failure.c (ffffffff814c4a10)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/userfaultfd.c (ffffffff814d08c0)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/memremap.c (ffffffff814d507d)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/dax.c (ffffffff81566f35)
Location: include/linux/memcontrol.h:577
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/filemap.c (ffff8000102b273c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b7818)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffff8000102bbf7c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffff8000102cdd80)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffff8000102d3b38)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffff8000102efde8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffff8000102fa33c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffff800010309724)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffff8000103465a8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001145bd38)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffff80001040a340)
Location: include/linux/memcontrol.h:354
Inline: True
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
In mm/filemap.c (c04df9b8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c04e4454)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (c04e6fa4)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c04f7c40)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (c04fba90)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (c05136b0)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (c051bc88)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c052621c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c054b1a8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c1534284)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
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
In mm/filemap.c (c000000000368d14)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c00000000036f618)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (c000000000373888)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (c00000000038b980)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (c000000000392900)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (c0000000003b48dc)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (c0000000003c44a8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c0000000003d8de8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (c000000000424538)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c000000001386544)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (c0000000005164fc)
Location: include/linux/memcontrol.h:354
Inline: True
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
In mm/filemap.c (ffffffe0001d8072)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffe0001dbb10)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001de1ba)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffe0001ec2b8)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffe0001ef86a)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffe000203800)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffe000209afc)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffe0002139de)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffe000239468)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe00001959c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffe0002b3f20)
Location: include/linux/memcontrol.h:354
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
In mm/filemap.c (ffffffff8121dbae)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81222088)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81224cbc)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81235129)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff81239a32)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff81250859)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8125b6a6)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8126c126)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129dd37)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828cb920)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff81341e51)
Location: include/linux/memcontrol.h:354
Inline: True
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
In mm/filemap.c (ffffffff81210d78)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81215238)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81217e5e)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81228199)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff8122ca62)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff812437d9)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8124dc86)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8125e196)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8128f8c7)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828c4045)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff81332809)
Location: include/linux/memcontrol.h:354
Inline: True
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
In mm/filemap.c (ffffffff8121b94e)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8121fe28)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81222a5c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff81232ec9)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff812377d2)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff8124e5f9)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81259446)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81269ec6)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff8129bb47)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828de6a0)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff8133f921)
Location: include/linux/memcontrol.h:354
Inline: True
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
In mm/filemap.c (ffffffff8122a9a5)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8122ef08)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffff81231c3c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/vmscan.c (ffffffff812423d9)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:lruvec_lru_size
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/shmem.c (ffffffff81246d13)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/workingset.c (ffffffff8125df69)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81268e46)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81279836)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/slub.c (ffffffff812aba2c)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff828e3ab7)
Location: include/linux/memcontrol.h:354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_init
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_get_max
  - mm/memcontrol.c:mem_cgroup_update_lru_size
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In fs/dax.c (ffffffff813532ed)
Location: include/linux/memcontrol.h:354
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
