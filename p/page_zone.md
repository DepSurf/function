# Function: <code>page_zone</code>

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
In arch/x86/mm/init_64.c (ffffffff81818d31)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8107d9c4)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/sched/wait.c (ffffffff810c36e7)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (ffffffff810d0747)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff8118c4fc)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:__lock_page
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:unlock_page
  - mm/filemap.c:wait_on_page_bit_killable
```
```
In mm/page_alloc.c (ffffffff81191780)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:is_free_buddy_page
```
```
In mm/swap.c (ffffffff8119c94a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811a28bd)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/vmstat.c (ffffffff811ac49f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
```
```
In mm/compaction.c (ffffffff811b4c4d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff811b9cf9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:workingset_activation
```
```
In mm/mlock.c (ffffffff811c2ca9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811cae76)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/mempolicy.c (ffffffff811dff52)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/slub.c (ffffffff811e90d3)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff811ef17f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In mm/migrate.c (ffffffff811f105c)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f72a1)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fec8b)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In mm/memory-failure.c (ffffffff812020a3)
Location: include/linux/mm.h:840
Inline: True
```
```
In mm/page_isolation.c (ffffffff81203a7f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/cma.c (ffffffff81f8e379)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81208174)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In drivers/base/memory.c (ffffffff815610e1)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff8189283c)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8107fb0d)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/sched/wait.c (ffffffff810c705f)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (ffffffff810d5277)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff8119fdf7)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:unlock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - mm/filemap.c:wait_on_page_bit
```
```
In mm/page_alloc.c (ffffffff811acd25)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811b3892)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811b8e97)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff811c6297)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811cee7a)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff811df15b)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff811fa10a)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/mempolicy.c (ffffffff811fe4f2)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/slub.c (ffffffff81208bcd)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff8120ed75)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:zone_can_shift
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8121359d)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81217a33)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8121afe8)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8122479e)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81225e01)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff81228f83)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff81fb889b)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8122dba5)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In drivers/base/memory.c (ffffffff815b5903)
Location: include/linux/mm.h:931
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff818c7186)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff81084245)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810dbe19)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811bd27e)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811c3f22)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811c94d7)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff811d63d9)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811def9b)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff811eef70)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff8120abdb)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8120f192)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/slub.c (ffffffff8121ac46)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff81220e6b)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:zone_can_shift
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81225902)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81229fe3)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122c6fc)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81236d87)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812383e2)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff8123b515)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff81ff5203)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812400ee)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In drivers/base/memory.c (ffffffff815e4c17)
Location: include/linux/mm.h:920
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff818fe8f6)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff810812a5)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810dac59)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811c54de)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811cc312)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d1fb2)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff811df10b)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811e8c2d)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff811f9f19)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff81215eeb)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/memory_hotplug.c (ffffffff8122c784)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81230cd2)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235b32)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81238f5b)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81242839)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81244841)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812472c2)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff820d7995)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8124bfa9)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In drivers/base/memory.c (ffffffff815f96d7)
Location: include/linux/mm.h:962
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff81988a20)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff81087b8a)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810e33cf)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811da27e)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811e12f5)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811e744f)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff811f4e16)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811ff065)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff81212450)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff81230a84)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81235d13)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81989991)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8124ea1f)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812548d9)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81257652)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81262676)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812646f9)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8126742a)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff826e0672)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8126c356)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff8126e309)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In drivers/base/memory.c (ffffffff816616ba)
Location: include/linux/mm.h:1013
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff819e5374)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8108aef1)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810ed11a)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811fab65)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff81202a3b)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812089af)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff81216031)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81220421)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff812331ab)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff8125270b)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81258d13)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff819e6281)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81272863)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812786c3)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127b790)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81286836)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8128875d)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8128bd0d)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff8270ac15)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81290ef3)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff81292813)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1092
Inline: True
```
```
In drivers/base/memory.c (ffffffff8169d164)
Location: include/linux/mm.h:1092
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
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
In arch/x86/mm/init_64.c (ffffffff81a20594)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff81093058)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810f8779)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/memremap.c (ffffffff811fa248)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/page_alloc.c (ffffffff8120d3a5)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff812153bb)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121b64f)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/vmstat.c (ffffffff81228f31)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812333a1)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff81246979)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff8126696b)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8126d103)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81a216d4)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81286e1b)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cd40)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812903ac)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8129b7a6)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8129da2d)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812a0c6d)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff828c1df9)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812a5f13)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1160
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bdaa4)
Location: include/linux/mm.h:1160
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In arch/x86/mm/init_64.c (ffffffff81a90b17)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8109718f)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff81100daa)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff81224ddd)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff81238c0d)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81245bb8)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff81258c04)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81273805)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff81281bf4)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81288573)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81a9207b)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
```
```
In mm/migrate.c (ffffffff812a17b3)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a8590)
Location: include/linux/mm.h:1228
Inline: True
```
```
In mm/khugepaged.c (ffffffff812ab4c1)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff812b895d)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812bbf3e)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff828db206)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/memremap.c (ffffffff812c269c)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1228
Inline: True
```
```
In drivers/base/memory.c (ffffffff816f89b2)
Location: include/linux/mm.h:1228
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffff8109cc6f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110d20a)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff81232b6d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff81246efd)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8125407b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff812670d4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81282675)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff81291603)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812980e3)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81ac980b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812b2bc1)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9a70)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffffffff812bcc66)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812ca83d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812cde1e)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d0871)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828e363c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816608e0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff8171ce22)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffff810a38af)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff811183f2)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff81260054)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff81274767)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81280c1b)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff81297285)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff812b47e5)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81bc5ae1)
Location: include/linux/mm.h:1416
Inline: True
```
```
In mm/mempolicy.c (ffffffff812cba12)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff812e113e)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812e814b)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ee5c4)
Location: include/linux/mm.h:1416
Inline: True
```
```
In mm/memory-failure.c (ffffffff81300484)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff81304135)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813072ad)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8130a83a)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1416
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817105cf)
Location: include/linux/mm.h:1416
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff81bdf889)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8126aa67)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmstat.c (ffffffff8127efba)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8128af2b)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff812a2237)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff812c0175)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81c3eac7)
Location: include/linux/mm.h:1479
Inline: True
```
```
In mm/mempolicy.c (ffffffff812d73b2)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff812eb9df)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812f34d5)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f9c37)
Location: include/linux/mm.h:1479
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130ec88)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff8130fd7b)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81312fed)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8131624a)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - mm/memremap.c:pageunmap_range
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d1af)
Location: include/linux/mm.h:1479
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff81bd17ad)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8126fc47)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmstat.c (ffffffff8128413a)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81290327)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff812a7ac7)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff812c58e5)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81c30b96)
Location: include/linux/mm.h:1535
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812c664b)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In mm/mempolicy.c (ffffffff812deb62)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/migrate.c (ffffffff812f98a5)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff813003ba)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813144d2)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff81315ed0)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81319232)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8131c647)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710f1f)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff817d20a4)
Location: include/linux/mm.h:1535
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
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
In kernel/power/snapshot.c (ffffffff81caa3ed)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/swap.c (ffffffff812acf19)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmstat.c (ffffffff812c28cf)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812d0377)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff812e90d7)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81309ff5)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81d4f4a9)
Location: include/linux/mm.h:1546
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130af99)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/mempolicy.c (ffffffff81326084)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/migrate.c (ffffffff8133dd34)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134a022)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135f895)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff81361fbf)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813658f5)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff81369940)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178da1f)
Location: include/linux/mm.h:1546
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff81e5a806)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page-writeback.c (ffffffff812ff0a6)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81304695)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
```
```
In mm/vmstat.c (ffffffff8131f9ab)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813301ef)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff8134c23b)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
```
```
In mm/page_alloc.c (ffffffff81372d35)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff81f1f407)
Location: include/linux/mm.h:1481
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81374689)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/mempolicy.c (ffffffff81395147)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/migrate.c (ffffffff813b16a5)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813c0a69)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813db83c)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff813dea2d)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813e1db2)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff813e72d7)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61d9)
Location: include/linux/mm.h:1481
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff81185c80)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page-writeback.c (ffffffff8136972e)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f84a)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmstat.c (ffffffff8139355b)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813a6e88)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff813c4dbb)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
```
```
In mm/page_alloc.c (ffffffff813f04b5)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff820c862d)
Location: include/linux/mm.h:1594
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff813f17f9)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/mempolicy.c (ffffffff81414ce7)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/migrate.c (ffffffff81432a15)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81442972)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8146076c)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814656ed)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81469395)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8146ef42)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16b09)
Location: include/linux/mm.h:1594
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff81196e50)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page-writeback.c (ffffffff8139b8cb)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a196a)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmstat.c (ffffffff813c5edb)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813da678)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff813f9329)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
```
```
In mm/page_alloc.c (ffffffff81424045)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff8214c8ad)
Location: include/linux/mm.h:1807
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81425339)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/mempolicy.c (ffffffff81448277)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/migrate.c (ffffffff814673b4)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814782c0)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8149691c)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff8149b16d)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8149e324)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff814a3704)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb99)
Location: include/linux/mm.h:1807
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/power/snapshot.c (ffffffff811a5902)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page-writeback.c (ffffffff813c42f4)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb5ee)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmstat.c (ffffffff813f08db)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81404568)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff81424ed6)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
```
```
In mm/page_alloc.c (ffffffff81450ee5)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff8222f3bd)
Location: include/linux/mm.h:1862
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81452579)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/hugetlb.c (ffffffff8391a945)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
```
```
In mm/mempolicy.c (ffffffff81485ac7)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
```
```
In mm/migrate.c (ffffffff81496681)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a7a00)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff814c603c)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814ca84d)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff814cd456)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff814d45a4)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab23a9)
Location: include/linux/mm.h:1862
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/fork.c (ffff8000100f106c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/swap.c (ffff8000102c2b3c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffff8000102da2a0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffff8000102e9a2c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffff8000102fe29c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffff80001031abec)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffff80001032e7d4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff800010336f30)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffff800010d9c8ec)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffff800010353004)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035a1a8)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffff80001035df28)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffff80001036de94)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffff8000103722a4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffff800010375c80)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffff80001145cb6c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b03c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/fork.c (c0350194)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (c03bfe98)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
```
```
In mm/swap.c (c04edc90)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/mmzone.c (c05005ac)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mmzone.c:memmap_valid_within
```
```
In mm/vmstat.c (c0501124)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (c050d2c4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (c051d300)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (c0535008)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/migrate.c (c0550ed4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/page_isolation.c (c055efac)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (c0561f60)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (c1534ea4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In drivers/virtio/virtio_balloon.c (c0947544)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/fork.c (c000000000136c88)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/swap.c (c00000000037cc54)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (c00000000039ab18)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (c0000000003ae8ac)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (c0000000003c9b18)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (c0000000003ee3d8)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (c00000000040772c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c0000000004112b0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (c000000000430720)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (c000000000439bc0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000443c40)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (c0000000004498b4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (c00000000045ee54)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (c000000000463b90)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (c000000000468670)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (c000000001387178)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6608)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (c0000000009b1b40)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffe0000be6f6)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/swap.c (ffffffe0001e3e30)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffe0001f4554)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffe0002000fe)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffe00020c81c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffe000220158)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffe00022c818)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffe00023e9e6)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/page_isolation.c (ffffffe00024b4f8)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffe00024e410)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffe000019b4a)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fc72)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
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
In kernel/fork.c (ffffffff8109658f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110542a)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8122b1bd)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff8123f54d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8124c6cb)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff8125f724)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff8127acc5)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff81289be3)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812906c3)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81a6867b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812ab1a1)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b2050)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b5246)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c2e1d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812c63fe)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c8e51)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828cc4f0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626750)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff816e3152)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffff8108500f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810f66ca)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8121e2cd)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff8123254d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8123f66b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff81251b44)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff8126cba5)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff8127ba13)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81282343)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81a2513b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff8129ca1f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a33e0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffffffff812a6277)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812b3e6d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812b743e)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812b9e91)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828c4c0c)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161add0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff816bd792)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffff8109653f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff811036da)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff81228f5d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff8123d2ed)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8124a46b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff8125d4c4)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81278a65)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff812879f3)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128e4d3)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81ad4a8b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812a8fb1)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812afe60)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffffffff812b3056)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c0c2d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812c420e)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c6c61)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828df270)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654720)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff817102e2)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
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
In kernel/fork.c (ffffffff8109e11f)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110eaca)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8123831d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmstat.c (ffffffff8124ca1d)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81259ccb)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffff8126ceaa)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81288655)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffffffff81297f90)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129e3ca)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffffffff81ae0f6b)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812b92cb)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812c01a0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In mm/khugepaged.c (ffffffff812c34ae)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812d16ed)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812d4cce)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d72bd)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828e4687)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1242
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f1a0)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/memory.c (ffffffff8172b442)
Location: include/linux/mm.h:1242
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
</details>
</li>
</ul>

## Differences
