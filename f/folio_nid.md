# Function: <code>folio_nid</code>

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
In mm/slub.c (ffffffff813ab1ce)
Location: include/linux/mm.h:1312
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
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff813b167a)
Location: include/linux/mm.h:1312
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
```
```
In mm/memcontrol.c (ffffffff813d55b8)
Location: include/linux/mm.h:1312
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
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
In mm/vmscan.c (ffffffff8137960d)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/hugetlb.c (ffffffff8141329d)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
  - mm/hugetlb.c:enqueue_hugetlb_folio
```
```
In mm/slub.c (ffffffff814272be)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
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
```
```
In mm/migrate.c (ffffffff814329ea)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
```
```
In mm/memcontrol.c (ffffffff8145b080)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In mm/hugetlb_cgroup.c (ffffffff8145dd9a)
Location: include/linux/mm.h:1400
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff813aa76a)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/swapfile.c (ffffffff81433eb5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/swapfile.c:__folio_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff814467fd)
Location: include/linux/mm.h:1599
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
In mm/mempolicy.c (ffffffff8144b08f)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/slub.c (ffffffff8145c25e)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
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
```
```
In mm/migrate.c (ffffffff81467389)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
```
```
In mm/huge_memory.c (ffffffff81478de8)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:free_transhuge_page
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff81490cd5)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
```
```
In mm/hugetlb_cgroup.c (ffffffff81493a84)
Location: include/linux/mm.h:1599
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff813d416a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/vmscan.c:get_pfn_folio
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
```
```
In mm/memory.c (ffffffff8141bef6)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8142efac)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/slub.c (ffffffff8145d4be)
Location: include/linux/mm.h:1653
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
```
```
In mm/swapfile.c (ffffffff8146d2b5)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/swapfile.c:__folio_throttle_swaprate
```
```
In mm/hugetlb.c (ffffffff814802a0)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:prep_and_add_bootmem_folios
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:alloc_surplus_hugetlb_folio
  - mm/hugetlb.c:prep_and_add_allocated_folios
  - mm/hugetlb.c:prep_and_add_allocated_folios
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:add_hugetlb_folio
  - mm/hugetlb.c:__remove_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff81487519)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/migrate.c (ffffffff8149ae9a)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:folio_migrate_flags
```
```
In mm/huge_memory.c (ffffffff814a83c8)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:folio_undo_large_rmappable
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff814af9f0)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814c0642)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff814c33d6)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
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
