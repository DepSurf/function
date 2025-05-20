# Function: <code>PageHead</code>

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
In kernel/futex.c (ffffffff810ffc23)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page_alloc.c (ffffffff81192572)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_compound_page
  - mm/page_alloc.c:__free_page_frag
```
```
In mm/swap.c (ffffffff8119c9c8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a2203)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b57a3)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2d0e)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (ffffffff811ca5ef)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
```
```
In mm/madvise.c (ffffffff811d1dda)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff811d28b3)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/hugetlb.c (ffffffff811da1d6)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:putback_active_hugepage
```
```
In mm/mempolicy.c (ffffffff811e028e)
Location: include/linux/page-flags.h:396
Inline: True
```
```
In mm/sparse.c (ffffffff811e3900)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff811e46e5)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/ksm.c:page_trans_compound_anon
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/slub.c (ffffffff811e8695)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/slub.c:on_freelist
  - mm/slub.c:ksize
  - mm/slub.c:ksize
  - mm/slub.c:check_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:kfree
  - mm/slub.c:kfree
```
```
In mm/memory_hotplug.c (ffffffff8181a46a)
Location: include/linux/page-flags.h:396
Inline: True
```
```
In mm/migrate.c (ffffffff811f0862)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f3d0c)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fa78a)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/hugetlb_cgroup.c (ffffffff81200fdf)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812015a6)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory-failure.c:set_page_hwpoison_huge_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_isolation.c (ffffffff81204123)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/page_idle.c (ffffffff81208230)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/direct-io.c (ffffffff81249890)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/page.c (ffffffff812880dc)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
```
```
In block/bio.c (ffffffff813b19e9)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_check_pages_dirty
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
In mm/filemap.c (ffffffff811a1d5d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811a784b)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_page_frag
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff811b1fb4)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811b4531)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811bcb20)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c0ce1)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811c4972)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff811cfd37)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811d4570)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811df129)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff811e6c0e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff811ef8bb)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff811f0599)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/hugetlb.c (ffffffff811fe1ee)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff811fe56e)
Location: include/linux/page-flags.h:473
Inline: True
```
```
In mm/slub.c (ffffffff8120aec3)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff8120ed2f)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8121356d)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81217e11)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81224150)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff81225c6e)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81227b81)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:set_page_hwpoison_huge_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff812290d1)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812a4501)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812b5494)
Location: include/linux/page-flags.h:473
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/filemap.c (ffffffff811b1bd7)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811b7c35)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff811c2615)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811c5b42)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811cd1f6)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d12dc)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811d4a82)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff811dfd6d)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811e45ff)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811eef40)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff811f6d3a)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f7fae)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:__page_check_address
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8120023f)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff81200f69)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap
```
```
In mm/hugetlb.c (ffffffff8120ecbe)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8120f2ae)
Location: include/linux/page-flags.h:489
Inline: True
```
```
In mm/slub.c (ffffffff8121cf0e)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81220e13)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812258d2)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122a3d2)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81236650)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff8123824e)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8123a10e)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:set_page_hwpoison_huge_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff8123b671)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812b9e61)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812cacf5)
Location: include/linux/page-flags.h:489
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/filemap.c (ffffffff811b7e1b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bfa76)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff811caa98)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811cde42)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_page
```
```
In mm/vmscan.c (ffffffff811d5ee0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d9d90)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811dd8a2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff811e9a6e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/swap_slots.c (ffffffff811ec987)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/debug.c (ffffffff811eea43)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff811f9e33)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81202277)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8120350e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8120ae3d)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swap_state.c (ffffffff8120be87)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8120e0a9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/hugetlb.c (ffffffff8121a55e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8121abee)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/slub.c (ffffffff81228fee)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff8122c73f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81230ca2)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81235fc4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812425e3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff81243eb6)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81245d46)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff81247293)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812c7551)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d8185)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff81465c10)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In mm/filemap.c (ffffffff811cc4aa)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811d45a9)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff811df808)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811e3219)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff811eb400)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811efa74)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff811f3322)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff811ffdba)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/swap_slots.c (ffffffff81202ce7)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/debug.c (ffffffff81204eb3)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81212283)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8121ae77)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121c059)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8122412f)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/page_io.c (ffffffff81224a14)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81225488)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81229dda)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/zswap.c (ffffffff8122d633)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812356ce)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81238bdd)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81242ef9)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81989bf2)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8124e9fc)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:new_page_node
  - mm/migrate.c:new_page_node
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81254d35)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81262423)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff81263d16)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81265d6a)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_isolation.c (ffffffff812673e7)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff812eae31)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fc885)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff81491d1d)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
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
In mm/filemap.c (ffffffff811ed890)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811fa2d8)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff81201eb6)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81204874)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8120cbd7)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81210ff0)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81214561)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff812211db)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81225dee)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff81232fbb)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8123ccce)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123e0ee)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff81244e8a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff81246e9d)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81247a28)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8124b09e)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8124ec5c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812506a1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81258715)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8125c0ad)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812688ce)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff819e65e5)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8127282c)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81278bea)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812864e3)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff81288025)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8128a0e8)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff8128bcd7)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff81318481)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a483)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff814c787a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff819cb57a)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff811fee82)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff8120c9e9)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap.c (ffffffff81214836)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81217234)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8121fa9d)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122309a)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81227431)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff81234228)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff812394d8)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/mlock.c (ffffffff8124678e)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125119e)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81252681)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff812594da)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff8125b2cc)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8125bfea)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8125f6f5)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8126313c)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81264b71)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8126cde5)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8127096d)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff8127d370)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a2188f)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff81286de4)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8128e17f)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8129b443)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff8129cf65)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8129f060)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812a0c37)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/proc/task_mmu.c (ffffffff8132f354)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813417a3)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff814db4ba)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff81a047cb)
Location: include/linux/page-flags.h:517
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff81218652)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81224513)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81226b49)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8122f20a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81233a26)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81237121)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff81243fbf)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124a566)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124d7ed)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81258a45)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81263481)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126480d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81272db7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127541d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff81276418)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812771ba)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a357)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8127e0ac)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8127f791)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81288215)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8128bb41)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81298a4a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a922d0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a177a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a8af1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b6684)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/hugetlb_cgroup.c (ffffffff812b8115)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812b88f6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812bbed7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8132e01b)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81356f60)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81369bc3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff81506e71)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffff81a74cf7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8122285c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812322a3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812349bd)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123d39a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81241c29)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81245391)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff8125247f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81258a06)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125bd1f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81266f15)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81271c31)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8127307d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81281c17)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff81284427)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff81285f08)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81286c9a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81289e37)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff8128dafc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8128f581)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81297e15)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8129b721)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812a88a9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ac9a60)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b2b88)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ba071)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c8554)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9ff5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812ca7d6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812cddb7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812d6eb9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81341251)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff8136f530)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81381de3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff81524f77)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81aab8c7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8124ff87)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:page_cache_delete
  - mm/filemap.c:page_cache_delete
```
```
In mm/readahead.c (ffffffff8125cc18)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8125f428)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81262019)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81265960)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126ecea)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81272ee1)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff81282cd8)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/workingset.c (ffffffff81286e95)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81287138)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81287dd4)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/mlock.c (ffffffff8129718b)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812a2261)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a6b24)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812b400b)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff812b5d12)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff812b8228)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812b921a)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bc6b9)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812c05bc)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812c2221)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812cb4e5)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/mempolicy.c (ffffffff812cf2a1)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812ddc0a)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff812e10ba)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e8106)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812eec4f)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff812f3622)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812fdde5)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffd35)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81300416)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813040c7)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff8130c002)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/mpage.c (ffffffff81365559)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/io_uring.c (ffffffff8137c35a)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/iomap/buffered-io.c (ffffffff813ab560)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
```
In fs/proc/task_mmu.c (ffffffff813b6bf9)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813cc413)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/readpage.c (ffffffff8141875b)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/fuse/file.c (ffffffff81475e18)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In lib/iov_iter.c (ffffffff815897bb)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In net/xdp/xsk.c (ffffffff81ba71d7)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8125a1b5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:page_cache_delete
  - mm/filemap.c:page_cache_delete
```
```
In mm/readahead.c (ffffffff81266f98)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81269a28)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8126c320)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8127033a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127a100)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff8127d6b1)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In mm/compaction.c (ffffffff8128ccc5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/workingset.c (ffffffff81291196)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81291390)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812919d1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff81297a0f)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a213b)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812adba5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b1fc4)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812bfa9f)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff812c178b)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In mm/page_io.c (ffffffff812c38f2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff812c4f5e)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812c7b75)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812cbfec)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812cdf1a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812d7105)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812dad21)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812e6bc1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff812ebc62)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812f349b)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812f9281)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff812fee02)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130a276)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c0d5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8130ed8a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:__get_hwpoison_page
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff81317ec2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff81351d97)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/buffer.c (ffffffff81367617)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3bd)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/mpage.c (ffffffff81372429)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/io_uring.c (ffffffff8138a52a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813bc08f)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff813c8003)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813de055)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff814056e8)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81408427)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d2d)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142aed3)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c6a4)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e574)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8149136a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In block/bio.c (ffffffff8155aac0)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a5b0f)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b4f8)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81bb694a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8125fdd5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff8126bbdb)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff8126d818)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812711c4)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812760f1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127f254)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff81282831)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In mm/compaction.c (ffffffff81291e51)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/workingset.c (ffffffff812967b1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81bd9350)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8129709c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a17b0)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a79cb)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812b3011)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b7694)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812c51ff)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81c2d873)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff812c8681)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In mm/page_io.c (ffffffff812caadb)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812cbc0c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812ce4c5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812d2b9c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812d45ba)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812de6f5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812e2581)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812ee373)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffff812f9864)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81300138)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813051c1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81310af5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff813126d5)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813150e0)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff8131e0b2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff81358ab9)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/buffer.c (ffffffff8136e059)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/direct-io.c (ffffffff81375c6f)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/mpage.c (ffffffff81378509)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/io_uring.c (ffffffff813915e2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813c356c)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff813cf033)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813e4e43)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff8140ba26)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8140e739)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142852f)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a45)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433373)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484048)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814964c2)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/fuse/file.c:__readahead_batch
  - fs/fuse/file.c:__readahead_batch
```
```
In block/bio.c (ffffffff815630c7)
Location: include/linux/page-flags.h:570
Inline: True
```
```
In lib/iov_iter.c (ffffffff815acc21)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e703)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81ba58ea)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8129c745)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/readahead.c (ffffffff812a88ae)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff812a9e88)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812ae704)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812b25da)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bd648)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff812c1065)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/util.c:copy_huge_page
```
```
In mm/compaction.c (ffffffff812d15db)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/workingset.c (ffffffff812d6f1b)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81cbbd92)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d7a4f)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e277f)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:unmap_mapping_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e8feb)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:__munlock_isolation_failed
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff812f4ba1)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f9da4)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8130973f)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:prep_compound_page
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81d4c15a)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff8130d603)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In mm/page_io.c (ffffffff8130faeb)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff81310d4c)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81313a55)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81318570)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff8131a8d1)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81325a55)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff813297a4)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff813365ae)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffff8134352d)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81349d88)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134ef3d)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8135bdc6)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e135)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff81361184)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff8136b5d2)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff813a70ef)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/buffer.c (ffffffff813bcdbf)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/direct-io.c (ffffffff813c20b4)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/mpage.c (ffffffff813c4de9)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/io_uring.c (ffffffff813df3ee)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff8141245a)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff8142051a)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81436a13)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff8145d276)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8146160f)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c244)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485276)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814868e3)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff814db196)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In fs/fuse/file.c (ffffffff814ef02b)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff815c6c85)
Location: include/linux/page-flags.h:590
Inline: True
```
```
In lib/iov_iter.c (ffffffff8161985a)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8be6)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81c73498)
Location: include/linux/page-flags.h:590
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/events/uprobes.c (ffffffff812e5deb)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f44d0)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:filemap_unaccount_folio
  - mm/filemap.c:perf_trace_mm_filemap_op_page_cache
  - mm/filemap.c:trace_event_raw_event_mm_filemap_op_page_cache
```
```
In mm/page-writeback.c (ffffffff812fef44)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_write_one
```
```
In mm/folio-compat.c (ffffffff81300a52)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff81301ee6)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/readahead.c:ondemand_readahead
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81303248)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308d0d)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
```
In mm/vmscan.c (ffffffff8130f3ba)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/shmem.c (ffffffff8131921c)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131dfe5)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_mapcount
```
```
In mm/compaction.c (ffffffff81331c39)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/workingset.c (ffffffff813366dc)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/debug.c (ffffffff81e6da3b)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81337c8d)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff81342f65)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff8134c477)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d60)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbbe)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8136e032)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff81f1bb3a)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff81375fdf)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff8137a501)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff8137bbb0)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8137f0c9)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81383dca)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/zswap.c (ffffffff81385ea9)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81394745)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81398b88)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff813a04ca)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff813a7ee2)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
```
In mm/migrate.c (ffffffff813b5da6)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c079b)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c575f)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d54d1)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8565)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dd452)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813de2f5)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff813e3864)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_free_folio
```
```
In mm/page_idle.c (ffffffff813e633f)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/usercopy.c (ffffffff813e6cbf)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/memfd.c (ffffffff813e9645)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff8142c8e5)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_folio
```
```
In fs/fs-writeback.c (ffffffff81432729)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/remap_range.c (ffffffff81441fd3)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/buffer.c (ffffffff81446c50)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
```
```
In fs/direct-io.c (ffffffff81448f83)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/mpage.c (ffffffff8144bc3c)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff814720a1)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff8148a54b)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/proc/task_mmu.c (ffffffff81499e73)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b11b2)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff814dbdb6)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e0cc4)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/ext4/move_extent.c (ffffffff814fe8d3)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085c6)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a0e6)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8153fd85)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff81554873)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568d56)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157ed70)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff81671bf3)
Location: include/linux/page-flags.h:786
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e90a4f)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff816e6be4)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:page_copy_sane
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2b0e)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81e16005)
Location: include/linux/page-flags.h:786
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In kernel/sched/fair.c (ffffffff81152671)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In mm/filemap.c (ffffffff8135d883)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/truncate.c (ffffffff813713b3)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In mm/shmem.c (ffffffff8138a763)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In mm/compaction.c (ffffffff813a7766)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813ade9f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813baf03)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
```
```
In mm/mlock.c (ffffffff813c5007)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31aa)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d6879)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff813ea372)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__free_pages
  - mm/page_alloc.c:free_compound_page
```
```
In mm/memory_hotplug.c (ffffffff820c39dc)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/madvise.c (ffffffff813f3856)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/page_io.c (ffffffff813f7fa5)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:count_swpout_vm_event
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/zswap.c (ffffffff81403ce9)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8140aea4)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff8141628b)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8141fcda)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81435eec)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff814429a9)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144ac37)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d4d6)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814619c6)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff81464f85)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff8146b0c0)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In mm/memfd.c (ffffffff81471622)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/libfs.c (ffffffff814b9b5f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d256f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d7273)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/mpage.c (ffffffff814d97d6)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151bdbf)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/proc/task_mmu.c (ffffffff8152e117)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547b72)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inline.c (ffffffff81574d36)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815799bf)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81599113)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a30b6)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4606)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/squashfs/file.c (ffffffff815ee021)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6343)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c6c6)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In fs/fuse/file.c (ffffffff81624a30)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff8172d4b3)
Location: include/linux/page-flags.h:783
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81789c13)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0b2f)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d2598)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70928)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
```
```
In net/xdp/xsk.c (ffffffff81fed052)
Location: include/linux/page-flags.h:783
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffff813e3a7d)
Location: include/linux/page-flags.h:772
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141efa5)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff81425781)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/page_io.c (ffffffff8142aa84)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/zswap.c (ffffffff81436b4f)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8144557e)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/migrate.c (ffffffff814689d8)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81472282)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8148147b)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memory-failure.c (ffffffff8149726b)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff814a5b5d)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/page.c (ffffffff8157f791)
Location: include/linux/page-flags.h:772
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8140e2fa)
Location: include/linux/page-flags.h:788
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144bc75)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages
```
```
In mm/memory_hotplug.c (ffffffff8145276d)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/hugetlb.c (ffffffff8147b788)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
```
```
In mm/huge_memory.c (ffffffff814a2521)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memory-failure.c (ffffffff814c8701)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff814d6b0d)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/page.c (ffffffff815b81d1)
Location: include/linux/page-flags.h:788
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In arch/arm64/mm/flush.c (ffff8000100add20)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In mm/filemap.c (ffff8000102afe6c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c10fc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffff8000102c50a8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffff8000102ce7cc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d40f8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffff8000102d82d4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffff8000102eb0d0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffff8000102f07dc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffff8000102f30fc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffff8000102fe174)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffff800010307738)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffff800010308dc4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffff80001031a35c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffff80001031e850)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/page_io.c (ffff8000103204b0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffff800010321590)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swap_slots.c (ffff800010329ddc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffff80001032bf30)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffff800010336278)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffff80001033a630)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffff80001034a2ac)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffff800010353004)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff800010359388)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffff80001036b474)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffff80001036d920)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffff8000103701d8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffff800010372254)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffff80001037be44)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffff800010400374)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffff800010438ad8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffff80001044fff4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffff80001062f2e8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffff800010d7dfa0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/arm/mm/flush.c (c031eb88)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In mm/filemap.c (c04dccbc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (c04f3c38)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c04fc2b8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (c04ff6ec)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In mm/compaction.c (c050e6f4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (0)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In mm/gup.c (c0515470)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In mm/rmap.c (c05264a0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (c0531990)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap_state.c (c053986c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/slub.c (c054ebe4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (c0558d58)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/memfd.c (c0566bec)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (c05d2704)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In fs/proc/page.c (c0613280)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (c07d5c84)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (c0e78b2c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0b70)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6608)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In mm/filemap.c (c000000000364e40)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c00000000037c1a0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (c00000000037f8ec)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (c00000000038c5e8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c000000000393414)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (c000000000398018)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (c0000000003ac580)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0000000003b5348)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0000000003b9c30)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (c0000000003c9894)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (c0000000003d62e8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d8068)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (c0000000003ed470)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (c0000000003f2bd4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/page_io.c (c0000000003f5604)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (c0000000003f6be0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swap_slots.c (c000000000400ab8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (c000000000402acc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (c000000000410b3c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000414e3c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (c000000000429170)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (c000000000430924)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (c000000000439bac)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c0000000004444a0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (c00000000045ae30)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (c00000000045da98)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (c00000000045ee3c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (c000000000463b78)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (c000000000471340)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (c000000000509a8c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (c00000000054c2e0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (c000000000567ff4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (c0000000007d7010)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2558)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebdb5c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffe0001d53b4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffe0001e8f84)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffe0001eff8e)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffe0001f2ce0)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In mm/compaction.c (ffffffe0001ff5be)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffe000203fe4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffe000205472)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/page_vma_mapped.c (ffffffe000212902)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffe000213450)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffe00021fcbe)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/swap_state.c (ffffffe0002223f6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/hugetlb.c (ffffffe0002322b0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/slub.c (ffffffe00023bc0c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/migrate.c (ffffffe00023fb28)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/memcontrol.c (ffffffe000245786)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a5e0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffe00024b556)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffe0002525fc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffe0002acad0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e31e2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffe00045e7c2)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffe0008ab786)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8121aeac)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8122a8f3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8122d00d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff812359ea)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8123a279)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff8123d9e1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff8124aacf)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81251056)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125436f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8125f565)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8126a281)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126b6cd)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8127a267)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127ca77)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff8127e558)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127f2ea)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81282417)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff812860dc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81287b61)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812903f5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81293d01)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812a0e89)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a688d0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812ab168)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b2651)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c0b34)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812c25d5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812c2db6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c6397)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812cf499)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81339831)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81367b10)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8137a3c3)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff8151d557)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81a4ac57)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff8120e0ac)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121da13)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812200dd)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81228a54)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122d283)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff812309e1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff8123da6f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81243f96)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81246fbf)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff81251985)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8125c471)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125d96d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8126c157)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8126e927)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff81270388)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff81271104)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81273f37)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81277f3c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff812799c1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81282085)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81285911)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff81292969)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81a25390)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129c9e8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a39d8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b1bc4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3625)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812b3e06)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812b73d7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812c011d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8132a561)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813587b0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8136ae93)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff8150d847)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In drivers/nvdimm/pmem.c (ffffffff816ebcd8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_rw_page
```
```
In drivers/nvdimm/btt.c (ffffffff816ed3a3)
Location: include/linux/page-flags.h:550
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a07847)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff81218c4c)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81228693)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8122adad)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff8123378a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81238019)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff8123b781)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff8124886f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124edf6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125210f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8125d305)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff81268021)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126946d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81278007)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8127a817)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff8127c2f8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8127d08a)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81280227)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81283eec)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81285971)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128e205)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81291b11)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff8129ec99)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ad4ce0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a8f78)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b0461)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812be944)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812c03e5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812c0bc6)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812c41a7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812cd2a9)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81337301)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff813655e0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81377e93)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff815195e7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ab6b07)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/filemap.c (ffffffff81227d41)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81237a03)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8123a1ad)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_cleanup_page
```
```
In mm/vmscan.c (ffffffff81242cc1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81247664)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/util.c (ffffffff8124ae91)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/compaction.c (ffffffff81258094)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8125e776)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81261abf)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/mlock.c (ffffffff8126ccf0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_vma_mapped.c (ffffffff8127799f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81278f9d)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81287bf7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:free_compound_page
```
```
In mm/madvise.c (ffffffff8128a3f7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/page_io.c (ffffffff8128bec8)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:get_swap_bio
```
```
In mm/swap_state.c (ffffffff8128cc41)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8128ff21)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81293bcc)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
```
```
In mm/zswap.c (ffffffff81295691)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8129dfa5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:PageHeadHuge
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1921)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/slub.c (ffffffff812aeda5)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
```
```
In mm/memory_hotplug.c (ffffffff81ae11bb)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b9292)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812c07a1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812cf3b4)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_cancel_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0e75)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff812d1686)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff812d4c67)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/memfd.c (ffffffff812de02f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8134a3c1)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/proc/task_mmu.c (ffffffff81378cc0)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8138b943)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In lib/iov_iter.c (ffffffff81532de7)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ac2c47)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
</details>
</li>
</ul>

## Differences
