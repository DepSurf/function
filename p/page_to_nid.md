# Function: <code>page_to_nid</code>

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
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/page_alloc.c (ffffffff81197608)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/memory.c (ffffffff811bf6ea)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dae9d)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/mempolicy.c (ffffffff811e1122)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/ksm.c (ffffffff811e5e86)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff811ec679)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/migrate.c (ffffffff811f09d9)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In mm/huge_memory.c (ffffffff811f4b13)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/memory-failure.c (ffffffff81201e9c)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812040db)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:721
Inline: True
```
```
In drivers/base/node.c (ffffffff8181b681)
Location: include/linux/mm.h:721
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (0)
Location: include/linux/mm.h:721
Inline: True
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
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In kernel/sched/wait.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ac518)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/shmem.c (ffffffff811c05e5)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811c6786)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/list_lru.c (ffffffff811d39f6)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811d406f)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811db412)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ea791)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fe086)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8120163d)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204b4f)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff8120bddf)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff8120ee9b)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812136ed)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8121522d)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8121bf7f)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81222b92)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/memory-failure.c (ffffffff8122625c)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff812290a8)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:815
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a5590)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/base/node.c (ffffffff81895881)
Location: include/linux/mm.h:815
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (0)
Location: include/linux/mm.h:815
Inline: True
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
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bcaf8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/shmem.c (ffffffff811d0bc5)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811d5406)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/list_lru.c (ffffffff811e38ca)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811e3f4a)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811eaf88)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/mprotect.c (ffffffff811f4b4b)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fb1fe)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120eb56)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8121312d)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216c41)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff8121de18)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff81220f95)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81225a52)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8122783c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8122d72a)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81234f72)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memory-failure.c (ffffffff8123882c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff8123b648)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812baee0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/base/node.c (ffffffff818ca0cb)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (0)
Location: include/linux/mm.h:804
Inline: True
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
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c4cc8)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/shmem.c (ffffffff811d9165)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811de286)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/list_lru.c (ffffffff811edd1a)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811ee571)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff811f606d)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/mprotect.c (ffffffff811ffa0d)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/vmalloc.c (ffffffff81205f42)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/swap_state.c (ffffffff8120bd88)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812155b3)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8121e44d)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8122264f)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff812299d8)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff8122c850)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81230deb)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81233a1c)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff81239fb2)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812409f2)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/memory-failure.c (ffffffff812447ec)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:846
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c805d)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/base/node.c (ffffffff81901635)
Location: include/linux/mm.h:846
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (0)
Location: include/linux/mm.h:846
Inline: True
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
In arch/x86/mm/init_64.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d9aac)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/shmem.c (ffffffff811ee445)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff811f3d16)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__inc_node_page_state
```
```
In mm/compaction.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/list_lru.c (ffffffff81204185)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff812048c1)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8120dcd8)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/mprotect.c (ffffffff8121813d)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121ec66)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/swap_state.c (ffffffff8122537b)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81230184)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812396a2)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8123d9da)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81244b8a)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff8124812c)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8124eb49)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8125133d)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8125866b)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81260732)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/memory-failure.c (ffffffff81264693)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:897
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb91b)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/base/node.c (ffffffff8198b675)
Location: include/linux/mm.h:897
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (0)
Location: include/linux/mm.h:897
Inline: True
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
In arch/x86/mm/init_64.c (ffffffff819e5378)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8108af05)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810ed11e)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff811eb2d4)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811fab74)
Location: include/linux/mm.h:974
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
In mm/page-writeback.c (ffffffff811fe73c)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff812022ba)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8120cad7)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8120ed61)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81216034)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81220424)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/list_lru.c (ffffffff81224e33)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81225649)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff8122e750)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mlock.c (ffffffff812331ae)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff81239256)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123e90e)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8124091e)
Location: include/linux/mm.h:974
Inline: True
```
```
In mm/swap_state.c (ffffffff8124791e)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812587dd)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8125cc25)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81261394)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff812689bd)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff8126b9c2)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81272863)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81279735)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127d4bd)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81286839)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81288705)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff8128bd0d)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff8270ac18)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81290ef6)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff81292821)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/dcache.c (ffffffff812b73ab)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_free_external_name
```
```
In fs/proc/task_mmu.c (ffffffff81318dde)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:974
Inline: True
```
```
In drivers/base/node.c (ffffffff819e7f75)
Location: include/linux/mm.h:974
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff8169d179)
Location: include/linux/mm.h:974
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
In arch/x86/mm/init_64.c (ffffffff81a20598)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8109306c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810f877d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/memremap.c (ffffffff811fa1bb)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811fbe44)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff8120d3bf)
Location: include/linux/mm.h:1016
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
In mm/page-writeback.c (ffffffff8120f02f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81214c3c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121f946)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122164c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81228f34)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812333a4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/list_lru.c (ffffffff81237f43)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81238a5d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/memory.c (ffffffff81242667)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8124697c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff8124d7dc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81252ea2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8125520e)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/swap_state.c (ffffffff8125bec3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8126ceb1)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff81271505)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81275b6f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff8127d45d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81a216eb)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81286e1b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8128ddb5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81291c09)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8129b7a9)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_page_lruvec
```
```
In mm/memory-failure.c (ffffffff8129d9d5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812a0c6d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff828c1dfc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812a5f16)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/task_mmu.c (ffffffff8132fe8e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/base/node.c (ffffffff81a233e5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff816bdab9)
Location: include/linux/mm.h:1016
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
In arch/x86/mm/init_64.c (ffffffff81a90b35)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff810971a3)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff81100dae)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81213f46)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8121ebb0)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81223d99)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122f0fd)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81230eb3)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81238c10)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81245bbb)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff812494f2)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff8124a217)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff8124d8ba)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff8125145a)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff81258c07)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff8125f7e5)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81265210)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff812672bd)
Location: include/linux/mm.h:1084
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127381b)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff81277092)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff812882b9)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8128cb15)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8129176b)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff81298b3d)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81a9209a)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
```
```
In mm/migrate.c (ffffffff812a17b3)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a8735)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812acb67)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812b694e)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812b88c5)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812bbf3e)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff828db211)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812c1668)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812c25e3)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devm_memremap_pages_release
```
```
In fs/proc/task_mmu.c (ffffffff81357cc5)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1084
Inline: True
```
```
In drivers/base/node.c (ffffffff81a93535)
Location: include/linux/mm.h:1084
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff816f89c7)
Location: include/linux/mm.h:1084
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
In kernel/fork.c (ffffffff8109cc83)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110d20e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81221756)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122c650)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81231b29)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123d28d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123f0b8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81246f00)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff8124eb6e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff8125407e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff81257942)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81258667)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff8125bdf1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff8125fa0a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff812670d7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff8126dff5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81273ab8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff81275b2d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff8128268b)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff81286b72)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81297eb9)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff8129c745)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812a14eb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812a89ca)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81ac982a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812b2bc1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b9c56)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812be451)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812c881e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812ca7a5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812cde1e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d0877)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828e3647)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812d3598)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812d4547)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff8136fef5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816608e7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81acace5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff8171ce37)
Location: include/linux/mm.h:1098
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
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff811183f2)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81250c59)
Location: include/linux/mm.h:1272
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
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8125e6e9)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8126582d)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8126d445)
Location: include/linux/mm.h:1272
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
In mm/vmstat.c (ffffffff81274767)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff8127ce2e)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff81282c64)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8128617d)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81286e7b)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81287d8c)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/memory.c (ffffffff8128fec2)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81297285)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff8129e887)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a5032)
Location: include/linux/mm.h:1272
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
In mm/vmalloc.c (ffffffff812a6e5d)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff812b47e5)
Location: include/linux/mm.h:1272
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
Location: include/linux/mm.h:1272
Inline: True
```
```
In mm/swap_state.c (ffffffff812b96d6)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bfe85)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff812cb5a7)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812d0395)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812d6145)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812ddd2d)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff812e0fb8)
Location: include/linux/mm.h:1272
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
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ee7f6)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812f23a1)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812fa38a)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:mem_cgroup_update_tree
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/memory-failure.c (ffffffff813003e5)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff81304135)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813072ad)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/page_idle.c (ffffffff81309263)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8130a81f)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff813b7f20)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1272
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817105cf)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81bc31e5)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81a3aec3)
Location: include/linux/mm.h:1272
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page-writeback.c (ffffffff8126685c)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a8d2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812701a7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/vmstat.c (ffffffff8127efba)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8128d237)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8129042d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff8129115a)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81291989)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129a942)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff812a2237)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812a9c3d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812b46ad)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff812c0175)
Location: include/linux/mm.h:1314
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
Location: include/linux/mm.h:1314
Inline: True
```
```
In mm/swap_state.c (ffffffff812c48b2)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812cba35)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff812d71c7)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812dbeb5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812e1c45)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812e8c4d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memory_hotplug.c (ffffffff812eb9df)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812f34d5)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812f9e79)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812fe859)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81306291)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_update_tree
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/memory-failure.c (ffffffff8130ec88)
Location: include/linux/mm.h:1314
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
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81312fed)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8131622d)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pageunmap_range
```
```
In fs/proc/task_mmu.c (ffffffff813c9de0)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d1af)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81c3c115)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81a3d5e3)
Location: include/linux/mm.h:1314
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/swap.c (ffffffff8126fa92)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff81275f9e)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/vmstat.c (ffffffff8128413a)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81291c87)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff812958c0)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81296766)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812970d0)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129fe3b)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff812a7ac7)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812af0c8)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812ba84b)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff812c58e5)
Location: include/linux/mm.h:1370
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
Location: include/linux/mm.h:1370
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812c664b)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:shrink_zone_span
  - mm/memory_hotplug.c:shrink_zone_span
```
```
In mm/swap_state.c (ffffffff812cb543)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812d25d5)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff812de786)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/mempolicy.c (ffffffff812e3725)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812e93e5)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812f0d6d)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f98a5)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813003ba)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8130551c)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130c75c)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/memory-failure.c (ffffffff813144d2)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff81315ed0)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81319232)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8131c620)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff813d1440)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710f1f)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81c2e5b5)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff817d20a4)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
```
```
In net/core/page_pool.c (ffffffff81a24403)
Location: include/linux/mm.h:1370
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1374
Inline: True
```
```
In mm/swap.c (ffffffff812acd72)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:pagevec_lru_move_fn
```
```
In mm/vmscan.c (ffffffff812b2618)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/vmstat.c (ffffffff812c28cf)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812d1304)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff812d5f40)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff812d6eda)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812d7a83)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e3445)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff812e90d7)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812f08d7)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812fce4b)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff81309ff5)
Location: include/linux/mm.h:1374
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
Location: include/linux/mm.h:1374
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130af99)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/swap_state.c (ffffffff813105df)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81317ed5)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff81325b26)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/mempolicy.c (ffffffff8132a945)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8132c850)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/ksm.c (ffffffff81331315)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff81339540)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff81343751)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8134a022)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8134f357)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8135795c)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - mm/memcontrol.c:lock_page_lruvec_irqsave
  - mm/memcontrol.c:lock_page_lruvec_irq
  - mm/memcontrol.c:lock_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/memory-failure.c (ffffffff8135f895)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff81361fbf)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813658f5)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff81369940)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff81422940)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178da1f)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81d4cc75)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81ad89f9)
Location: include/linux/mm.h:1374
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff812f01fb)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff812ff0a6)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff81306e84)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8130f3fe)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff8131f9ab)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81330af7)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff81335418)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81336704)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81337ca8)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813447e2)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8134c23b)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mprotect.c (ffffffff81353c36)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81360844)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff81372d35)
Location: include/linux/mm.h:1304
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
Location: include/linux/mm.h:1304
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81374689)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/swap_state.c (ffffffff8137b17d)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813835b5)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff81394823)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_page
  - mm/hugetlb.c:__remove_hugetlb_page
  - mm/hugetlb.c:enqueue_huge_page
```
```
In mm/mempolicy.c (ffffffff8139a2f5)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139c8c0)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/ksm.c (ffffffff813a20ae)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff813ab1ce)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff813b5ee2)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c0a69)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff813c5ef8)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d55b8)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8129)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff813db83c)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff813dea2d)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813e1db2)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff813e72d7)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff81499a50)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61d9)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81f1c8a5)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81c599a0)
Location: include/linux/mm.h:1304
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff8135b59b)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8136972e)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff8136f6a0)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8137e716)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff8139355b)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813a7968)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff813ac1b8)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff813ad972)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/gup.c (ffffffff813ae97e)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813bc93c)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff813c4dbb)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mprotect.c (ffffffff813ce106)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff813dbd54)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff813f04b5)
Location: include/linux/mm.h:1392
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
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff820c862d)
Location: include/linux/mm.h:1392
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff813f17f9)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/swap_state.c (ffffffff813f8be5)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81400fd5)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff8141329d)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:enqueue_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413c61)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8141a315)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81421d0e)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff814272be)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff8143607c)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81442972)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8144aa4f)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8145b080)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/hugetlb_cgroup.c (ffffffff8145dd9a)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8146076c)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814656ed)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81469395)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff8146ef42)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff8152dc80)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16b09)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff820c48e5)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81e0f990)
Location: include/linux/mm.h:1392
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff8138d3fb)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff8139b8cb)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a17c0)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813afe00)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff813c5edb)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813daf3b)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff813e0558)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff813e1e62)
Location: include/linux/mm.h:1591
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
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f1333)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff813f9329)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff814029a6)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff814105f4)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff81424045)
Location: include/linux/mm.h:1591
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
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff8214c8ad)
Location: include/linux/mm.h:1591
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81425339)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/swap_state.c (ffffffff8142b9a1)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81433eb5)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/swapfile.c:__folio_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff814467fd)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_surplus_hugetlb_folio
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:enqueue_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (ffffffff814471d6)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144d8b5)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff814569ec)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff8145c25e)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff8146be89)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814782c0)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff81480b44)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff81490cd5)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__mod_lruvec_page_state
```
```
In mm/hugetlb_cgroup.c (ffffffff81493a84)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff8149691c)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff8149b16d)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8149e324)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff814a3704)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff815660dc)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb99)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff821486c5)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81e831d2)
Location: include/linux/mm.h:1591
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff813b6f77)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/filemap.c:folio_end_writeback
```
```
In mm/page-writeback.c (ffffffff813c42f4)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb441)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_note_cost_refault
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff813d92ed)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/vmstat.c (ffffffff813f08db)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff814050c9)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8140aeee)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del_obj
  - mm/list_lru.c:list_lru_add_obj
```
```
In mm/workingset.c (ffffffff8140c68f)
Location: include/linux/mm.h:1645
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
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141bef6)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff81424ed6)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff8142efac)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8143cf54)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff81450ee5)
Location: include/linux/mm.h:1645
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
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:split_free_page
```
```
In mm/shuffle.c (ffffffff8222f3bd)
Location: include/linux/mm.h:1645
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81452579)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/slub.c (ffffffff8145d4be)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__put_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/swap_state.c (ffffffff814650f9)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8146d2b5)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/swapfile.c:__folio_throttle_swaprate
```
```
In mm/zswap.c (ffffffff814707fa)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_lru_del
  - mm/zswap.c:zswap_lru_add
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/hugetlb.c (ffffffff814802a0)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:prep_and_add_bootmem_folios
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_surplus_hugetlb_folio
  - mm/hugetlb.c:prep_and_add_allocated_folios
  - mm/hugetlb.c:prep_and_add_allocated_folios
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:add_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (ffffffff814807db)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
```
In mm/mempolicy.c (ffffffff81487519)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_mpol
  - mm/mempolicy.c:alloc_pages_mpol
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/ksm.c (ffffffff814914dc)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff8149ad99)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814a7a00)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:folio_undo_large_rmappable
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff814aeb21)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_folio
```
```
In mm/memcontrol.c (ffffffff814c0642)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
  - mm/memcontrol.c:__mod_lruvec_kmem_state
  - mm/memcontrol.c:__lruvec_stat_mod_folio
```
```
In mm/hugetlb_cgroup.c (ffffffff814c33d6)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff814c66d7)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814ca84d)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff814cd456)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memremap.c (ffffffff814d45a4)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff8159e0c8)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab23a9)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff8222b085)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In net/core/page_pool.c (ffffffff81f43872)
Location: include/linux/mm.h:1645
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In kernel/fork.c (ffff8000100f1084)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (ffff8000102aed60)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bbf60)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffff8000102c17cc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce61c)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d1754)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffff8000102da2a4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffff8000102e4e34)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffff8000102e9a30)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffff8000102ef470)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffff8000102f048c)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffff8000102f3194)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffff8000102fa15c)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffff8000102fe2a8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffff800010305234)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309708)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffff80001030bf40)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffff80001031abec)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffff8000103213f8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffff800010336320)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff80001033b6ec)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffff800010340e28)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffff80001034a3f0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffff800010d9c908)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffff800010353008)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff80001035a4dc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035fdcc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffff80001036b740)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffff80001036de30)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffff8000103722a4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffff800010375c8c)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffff80001145cb80)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffff800010379150)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/task_mmu.c (ffff800010439cec)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b040)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffff800010d9f2c4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
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
In mm/vmscan.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1098
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
In kernel/fork.c (c000000000136c88)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/filemap.c (c0000000003621dc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c000000000373868)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (c00000000037b5a4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c00000000038c4a4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c00000000038f1c0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (c00000000039ab18)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (c0000000003a6a04)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (c0000000003ae8ac)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (c0000000003b3abc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (c0000000003b4ee0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (c0000000003b9bf4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (c0000000003bf508)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (c0000000003c9b18)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (c0000000003d2568)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d8dc8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (c0000000003dbf60)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (c0000000003ee3d8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (c0000000003f6974)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (c000000000410c08)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c00000000041645c)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (c00000000041e6a0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (c000000000429450)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (c000000000430720)
Location: include/linux/mm.h:1098
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
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c000000000443f84)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c00000000044ab68)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (c00000000045b270)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (c00000000045ee24)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (c000000000463b90)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (c000000000468670)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (c000000001387178)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (c00000000046c040)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (c00000000046dccc)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (c00000000054d5a4)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6608)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (c0000000009b0ff0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (c0000000009b1b40)
Location: include/linux/mm.h:1098
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
In mm/vmscan.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:1098
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
In kernel/fork.c (ffffffff810965a3)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110542e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81219da6)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81224ca0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8122a179)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812358dd)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81237708)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8123f550)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff812471be)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff8124c6ce)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8124ff92)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81250cb7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81254441)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff8125805a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8125f727)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff81266645)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126c108)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8126e17d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff8127acdb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff8127f1c2)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81290499)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff81294d25)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81299acb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812a0faa)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81a6869a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812ab1a1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b2236)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b6a31)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812c0dfe)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812c2d85)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812c63fe)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c8e57)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828cc4fb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812cbb78)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812ccb27)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff813684d5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626757)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81a69b55)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff816e3167)
Location: include/linux/mm.h:1098
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
In kernel/fork.c (ffffffff81085023)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810f66ce)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff8120cfb6)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81217e42)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff8121d299)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122894d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122a598)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff81232550)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff8123a16e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff8123f66e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff81242f32)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81243bf7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81247091)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff8124db18)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff81251b47)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff81258d29)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e178)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8126012d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff8126cbbb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff81270fe2)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff81282129)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff81286935)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8128b68b)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff81292a8a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81a2515a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff8129ca1f)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a35c6)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a7c01)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812b1e52)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812b3dd5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812b743e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812b9e97)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828c4c17)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812bc9f8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812bd997)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff81359815)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161add7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81a26025)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff816bd7a7)
Location: include/linux/mm.h:1098
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
In kernel/fork.c (ffffffff81096553)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff811036de)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81217b46)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81222a40)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81227f19)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123367d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812354a8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8123d2f0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff81244f5e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff8124a46e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8124dd32)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff8124ea57)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff812521e1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff81255dfa)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8125d4c7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff812643e5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81269ea8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8126bf1d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff81278a7b)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff8127cf62)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8128e2a9)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff81292b35)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812978db)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff8129edba)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81ad4aaa)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812a8fb1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b0046)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b4841)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812bec0e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812c0b95)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812c420e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c6c67)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828df27b)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812c9988)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812ca937)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff81365fa5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654727)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81ad5f65)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff817102f7)
Location: include/linux/mm.h:1098
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
In kernel/fork.c (ffffffff8109e133)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff8110eace)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/filemap.c (ffffffff81226c06)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81231c20)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81237259)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81242bbd)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812455b8)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/vmstat.c (ffffffff8124ca20)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/slab_common.c (ffffffff8125494e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/compaction.c (ffffffff81259cce)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/list_lru.c (ffffffff8125d6e2)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff8125e3d0)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81261b91)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (ffffffff81265888)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8126cead)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mprotect.c (ffffffff81273da5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81279818)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/vmalloc.c (ffffffff8127ba5d)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff8128866b)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap_state.c (ffffffff8128cb22)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffff8129e049)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812a2925)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812a76b1)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/slub.c (ffffffff812aeeca)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:process_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:discard_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff81ae0f8a)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffffffff812b92cb)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812c0386)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c5214)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812cf68e)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_page_lruvec
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/memory-failure.c (ffffffff812d1655)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812d4cce)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d72c5)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffff828e4692)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812da688)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff812db658)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/proc/task_mmu.c (ffffffff81379b90)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1098
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f1a7)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/base/node.c (ffffffff81ae2425)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/node.c:get_nid_for_pfn
```
```
In drivers/base/memory.c (ffffffff8172b457)
Location: include/linux/mm.h:1098
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
</details>
</li>
</ul>

## Differences
