# Function: <code>page_zonenum</code>

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
Location: include/linux/mm.h:687
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In kernel/sched/wait.c (ffffffff810c36ea)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/filemap.c (ffffffff8118c4ff)
Location: include/linux/mm.h:687
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
In mm/page_alloc.c (ffffffff81191783)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/swap.c (ffffffff8119c94d)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:add_page_to_unevictable_list
```
```
In mm/vmscan.c (ffffffff811a28c0)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/vmstat.c (ffffffff811ac4a2)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811b4c4d)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/compaction.c:pageblock_pfn_to_page
```
```
In mm/workingset.c (ffffffff811b9e1f)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/mlock.c (ffffffff811c31a8)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81819c5d)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/huge_memory.c (ffffffff811f72a4)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fec8e)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/page_isolation.c (ffffffff81203a82)
Location: include/linux/mm.h:687
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:687
Inline: True
```
```
In drivers/base/memory.c (ffffffff815610e4)
Location: include/linux/mm.h:687
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
In init/do_mounts.c (ffffffff81f825a4)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004123)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/init_64.c (ffffffff8189283f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In arch/x86/mm/gup.c (ffffffff81071605)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:undo_dev_pagemap
```
```
In kernel/fork.c (ffffffff8107fb10)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff81087074)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/wait.c (ffffffff810c7062)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (ffffffff810d527a)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810d7630)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81107769)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/relay.c (ffffffff81144c0f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/trace.c (ffffffff811586ef)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/core.c (ffffffff81189f64)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8119ade1)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a1456)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:unlock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - mm/filemap.c:wait_on_page_bit
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811acd28)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page-writeback.c (ffffffff811afd4d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811b115e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811b1fe9)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811b469f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811bcb2c)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811c31c8)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff811c629a)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811cff95)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/gup.c (ffffffff811d58c7)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d66b7)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de0da)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff811df2b4)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff811e0286)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/rmap.c (ffffffff811e837d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff811edb9d)
Location: include/linux/mm.h:736
Inline: True
```
```
In mm/madvise.c (ffffffff811ef585)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff811f0b4f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811f4751)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff811f7025)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff811fe2ab)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff811fe4f5)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204c21)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (ffffffff81208bd0)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff8120ed78)
Location: include/linux/mm.h:736
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
In mm/migrate.c (ffffffff81213344)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81218092)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121b867)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812247a1)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81227f62)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff81228f86)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8122b629)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff81fb8970)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/userfaultfd.c (ffffffff8122d3ab)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8122df47)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8122e4a5)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/exec.c (ffffffff81239d62)
Location: include/linux/mm.h:736
Inline: True
```
```
In fs/pipe.c (ffffffff8123bab1)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8123f24e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8125d030)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81267029)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:spd_release_page
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8126c897)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff812703e0)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff812750a6)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff81276eb1)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81285144)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff81287a87)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In fs/binfmt_elf.c (ffffffff8129599e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8129862a)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8129be0d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff812a546c)
Location: include/linux/mm.h:736
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cd15e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/symlink.c (ffffffff812edfab)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff812fdc8b)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81306ef0)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff813114d7)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff81313126)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/commit.c (ffffffff81318a2f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8132241b)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81324da8)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813286bb)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81338850)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81338b5e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81343e6d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8134daef)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In security/selinux/selinuxfs.c (ffffffff813805eb)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff813a4275)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff813f6560)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff81411493)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8141361d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81413df9)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81414a21)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814150d8)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8141687f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff81418508)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81418c4f)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81418e50)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81419133)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81419339)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81419593)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8141a6a5)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8141a8f4)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/iov_iter.c (ffffffff8144299d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1c61)
Location: include/linux/mm.h:736
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513ea1)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff8156a371)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff815705ad)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/base/memory.c (ffffffff815b587d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/base/memory.c:is_zone_device_section
  - drivers/base/memory.c:show_valid_zones
```
```
In drivers/scsi/scsicam.c (ffffffff8160126e)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/sg.c (ffffffff8161aeff)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/virtio_net.c (ffffffff8165245d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165c1db)
Location: include/linux/mm.h:736
Inline: True
```
```
In drivers/md/md.c (ffffffff816f601d)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/bitmap.c (ffffffff816fca69)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/sock.c (ffffffff8176abb3)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/core/skbuff.c (ffffffff8176f012)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8177dd0c)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/ip_output.c (ffffffff817c8ad7)
Location: include/linux/mm.h:736
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6b2a)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff817e15db)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv6/ip6_output.c (ffffffff81832dd8)
Location: include/linux/mm.h:736
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878fcd)
Location: include/linux/mm.h:736
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In init/do_mounts.c (ffffffff81fbe642)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100401d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/init_64.c (ffffffff818c7189)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In arch/x86/mm/gup.c (ffffffff81075176)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:undo_dev_pagemap
```
```
In kernel/fork.c (ffffffff81084248)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8108bfe0)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff810dbe1c)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810de1a8)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8110ef34)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8114ea8f)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81199355)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811aa541)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b117e)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bd281)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page-writeback.c (ffffffff811c040d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811c173c)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811c2618)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811c4d24)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811cd202)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811d3247)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff811d63dc)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811dffc3)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/gup.c (ffffffff811e58c7)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ed5fb)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811edeea)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff811ef0c8)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/mmap.c (ffffffff811f01d6)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/rmap.c (ffffffff811f9803)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff811fe49b)
Location: include/linux/mm.h:725
Inline: True
```
```
In mm/madvise.c (ffffffff811fff05)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8120154f)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8120527b)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff812079d5)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8120ed7b)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff8120f195)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216a25)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (ffffffff8121ac49)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff81220e6e)
Location: include/linux/mm.h:725
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
In mm/migrate.c (ffffffff812256ac)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a632)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122d005)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81236d8a)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8123a50c)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:shake_page
```
```
In mm/page_isolation.c (ffffffff8123b518)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8123db8d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff81ff52dd)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/userfaultfd.c (ffffffff8123f8cf)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff81240497)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812409d5)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff81244785)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8124caa1)
Location: include/linux/mm.h:725
Inline: True
```
```
In fs/pipe.c (ffffffff8124e851)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:generic_pipe_buf_get
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8125201e)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81270567)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8127a05e)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:spd_release_page
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8127f8f7)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81285840)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812889d3)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff8128ab74)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81299354)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff8129c675)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/binfmt_elf.c (ffffffff812aa600)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812ad0c0)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812b0bb2)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff812badc1)
Location: include/linux/mm.h:725
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e2eda)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/symlink.c (ffffffff81303f55)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff81313d0b)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8131ce94)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff813273b1)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff813290ca)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/commit.c (ffffffff8132ea23)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813382ab)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8133ac08)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e408)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e5f0)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e8fe)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813596d8)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81363403)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In security/selinux/selinuxfs.c (ffffffff8139706c)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/tomoyo/domain.c (ffffffff813badf0)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8140ff40)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff8142c82d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8142eb4d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8142f329)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8142ff51)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff81430608)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81431daf)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff81433a38)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff8143417f)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81434380)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81434663)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81434869)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81434ac3)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81435bd5)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81435e24)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/iov_iter.c (ffffffff8146007d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3c51)
Location: include/linux/mm.h:725
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815402d1)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81596ab0)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8159cc6d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/base/memory.c (ffffffff815e4b5d)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/base/memory.c:is_zone_device_section
  - drivers/base/memory.c:show_valid_zones
```
```
In drivers/scsi/scsicam.c (ffffffff8163095e)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/sg.c (ffffffff8164bb79)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/xen-netfront.c (ffffffff81689ff0)
Location: include/linux/mm.h:725
Inline: True
```
```
In drivers/md/md.c (ffffffff81727849)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/bitmap.c (ffffffff8172e639)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/sock.c (ffffffff81796c57)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8179c502)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff817ab67c)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/ip_output.c (ffffffff817f86c2)
Location: include/linux/mm.h:725
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806ace)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv4/tcp_output.c (ffffffff81811aab)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv6/ip6_output.c (ffffffff8186486c)
Location: include/linux/mm.h:725
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad6e8)
Location: include/linux/mm.h:725
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/mm/init_64.c (ffffffff818fe8f9)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff810812a8)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (ffffffff810dac5c)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811c54e1)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811caa9b)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d5eec)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811da046)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/vmstat.c (ffffffff811df10e)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff811e9d66)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/mlock.c (ffffffff811f9f19)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/hugetlb.c (ffffffff81215eee)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/memory_hotplug.c (ffffffff8122c787)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff81230cd5)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235b35)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812390da)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8124283c)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81244844)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffffffff812472c5)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/cma.c (ffffffff820d7a55)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8124bfac)
Location: include/linux/mm.h:781
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:781
Inline: True
```
```
In drivers/base/memory.c (ffffffff815f96d7)
Location: include/linux/mm.h:781
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
In init/do_mounts.c (ffffffff826a4749)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/init_64.c (ffffffff81988a29)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff81087b98)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8108fffd)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff810e33d8)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810e5505)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8111b9e4)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff811c03a5)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811c66c8)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811c9443)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ccd78)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/page_alloc.c (ffffffff811da291)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page-writeback.c (ffffffff811dd45a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811de908)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811df80b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:add_page_to_unevictable_list
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff811e23ad)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811eb40c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811f0671)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff811f4e1c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812000bb)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/gup.c (ffffffff81205aef)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81210864)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:_vm_normal_page
```
```
In mm/mincore.c (ffffffff8121125a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812125a1)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8121cf6c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81222326)
Location: include/linux/mm.h:798
Inline: True
```
```
In mm/madvise.c (ffffffff812242d8)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8122618a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81227d72)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8122d5ad)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8123579a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff81235d1d)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/ksm.c (ffffffff8123d842)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff819899b3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8124c1dc)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81255b1f)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812580e4)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8126267c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812661da)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/page_isolation.c (ffffffff81267438)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81268e17)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff826e0702)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/userfaultfd.c (ffffffff8126b83e)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8126c75b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cc35)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/hmm.c (ffffffff8126e36b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/read_write.c (ffffffff8127218c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127ad0c)
Location: include/linux/mm.h:798
Inline: True
```
```
In fs/pipe.c (ffffffff8127cb17)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81280444)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812a075b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812a9ebe)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812b2034)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812b5b71)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b8e93)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff812bace1)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812cadc8)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff812da888)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd986)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812e2490)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff812ec190)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8131f9e9)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c107)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81332e84)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8133a262)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81343013)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8135d501)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/commit.c (ffffffff8136830b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813717a6)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81374126)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81377d58)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81387e2e)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813882a9)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81392e1e)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8139cb20)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In security/tomoyo/domain.c (ffffffff813f7b78)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81448760)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff81465b6b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff81467f81)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81468805)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814692f6)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff81469a31)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8146b38d)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff8146d2d1)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff8146d5e0)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8146d847)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8146db28)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8146dd53)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8146e041)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8146efd6)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8146f358)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7cb3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81610576)
Location: include/linux/mm.h:798
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff81618097)
Location: include/linux/mm.h:798
Inline: True
```
```
In drivers/base/memory.c (ffffffff816616ba)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
```
```
In drivers/scsi/scsicam.c (ffffffff816ae586)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff816ffbed)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md.c (ffffffff817b2825)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff817baaec)
Location: include/linux/mm.h:798
Inline: True
```
```
In net/core/sock.c (ffffffff8182d523)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818378a3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81843618)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp.c (ffffffff818a6a05)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818b1051)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In init/do_mounts.c (ffffffff826cd75d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/init_64.c (ffffffff819e5378)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8108af05)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff81093cb6)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff810ed11e)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810eda0a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81128529)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/sockmap.c (ffffffff811cecfa)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In kernel/bpf/stackmap.c (ffffffff811d0e88)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811e072e)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811e6bea)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811e9497)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ede7a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:filemap_range_has_page
```
```
In mm/page_alloc.c (ffffffff811fab74)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page-writeback.c (ffffffff811fe5ab)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811ffebb)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81201f11)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81203af6)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120cbf6)
Location: include/linux/mm.h:840
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
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81211de2)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff81216034)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8122148f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/gup.c (ffffffff81226cb3)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81231274)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:_vm_normal_page
```
```
In mm/mincore.c (ffffffff81231d72)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812331ae)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8123ef20)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81244214)
Location: include/linux/mm.h:840
Inline: True
```
```
In mm/madvise.c (ffffffff81244f06)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248724)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124d646)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff812505fc)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812586d4)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81258d1a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81260e23)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff819e62d3)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8126fd01)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812799ac)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127db90)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81286839)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8128a02a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff8128bd0d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8128dd96)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff8270ac18)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/userfaultfd.c (ffffffff81290294)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff81291305)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812917f0)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/hmm.c (ffffffff81292830)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_release
```
```
In fs/read_write.c (ffffffff81297f10)
Location: include/linux/mm.h:840
Inline: True
```
```
In fs/exec.c (ffffffff812a1ab7)
Location: include/linux/mm.h:840
Inline: True
```
```
In fs/pipe.c (ffffffff812a3a97)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812a65a4)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812c6cb9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812d034d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812d9f76)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812dca09)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812e1a3c)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff812e385d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812f3ce2)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff813064fc)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309ea1)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8130e98f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff813199c7)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:840
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134dad5)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135a69f)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8135fbe9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8136882d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8137129b)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8138be58)
Location: include/linux/mm.h:840
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81396b86)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813a0051)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813a2b48)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6737)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6ada)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813b70dd)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c2e46)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813cbf27)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In security/tomoyo/domain.c (ffffffff81428b48)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8147b9cd)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff8149950a)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8149bd85)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c859)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149cfe0)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8149d9cf)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149ede4)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814a0eb8)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814a156d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a178c)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a1b23)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1cb9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a1f97)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814a3144)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a3462)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f01f9)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff815f261d)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8164a05c)
Location: include/linux/mm.h:840
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff81651992)
Location: include/linux/mm.h:840
Inline: True
```
```
In drivers/base/memory.c (ffffffff8169d179)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/base/memory.c:show_valid_zones
```
```
In drivers/scsi/scsicam.c (ffffffff816ea976)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8173d2b8)
Location: include/linux/mm.h:840
Inline: True
```
```
In drivers/md/md.c (ffffffff817f5d91)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81802b55)
Location: include/linux/mm.h:840
Inline: True
```
```
In net/core/sock.c (ffffffff81875ed7)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81881d6c)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8188daf3)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b3af2)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818baa96)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818bda48)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/ipv4/tcp.c (ffffffff818fbafd)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819066e0)
Location: include/linux/mm.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/xdp/xdp_umem.c (ffffffff819ccaf1)
Location: include/linux/mm.h:840
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
In init/do_mounts.c (ffffffff8288373b)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/init_64.c (ffffffff81a20598)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff8109306c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8109c033)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff810f877d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810f907a)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81133e0b)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811e0968)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f0b99)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811f7746)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/memremap.c (ffffffff811fa158)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ff47c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page_alloc.c (ffffffff8120d3bf)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/page-writeback.c (ffffffff8121123b)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8121278b)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81214891)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812163db)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121fac0)
Location: include/linux/mm.h:871
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
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81223c7f)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff81228f34)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812344e5)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/gup.c (ffffffff81239d4f)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81244a44)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:_vm_normal_page
```
```
In mm/mincore.c (ffffffff81245542)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8124697c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff81253511)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81258914)
Location: include/linux/mm.h:871
Inline: True
```
```
In mm/madvise.c (ffffffff8125955c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ccfa)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81261a61)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
```
```
In mm/zswap.c (ffffffff81264acc)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126cda6)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8126d10a)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812755fa)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a21726)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812843ab)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128dfa6)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81291673)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8129b7a9)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129ef9c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812a0c6d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812a36d8)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828c1dfc)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/userfaultfd.c (ffffffff812a5109)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812a6325)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a6810)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff812ad2ab)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b6877)
Location: include/linux/mm.h:871
Inline: True
```
```
In fs/pipe.c (ffffffff812b8be7)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812bb674)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812dbe89)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812e669d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812ef464)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff812f0c59)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f66e7)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff812f84ee)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81309390)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff8131bc8c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f6a1)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff81324e93)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_readpages
  - fs/iomap.c:iomap_readpages_actor
  - fs/iomap.c:iomap_readpages_actor
  - fs/iomap.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81330607)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:871
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81365c75)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813729eb)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8137b9c4)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81380cb3)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81389757)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813a49e8)
Location: include/linux/mm.h:871
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813af8e9)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813b8dde)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813bb93d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf517)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813d002a)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813d062d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813dc53d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813e4fe7)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff813ea989)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81445418)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81499ae9)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff814b376a)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814b6095)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b6b79)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b7300)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814b7cef)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b918c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
```
```
In block/partitions/msdos.c (ffffffff814bb278)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814bb92d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bbb4c)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbee4)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bc083)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bc357)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814bd324)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd642)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a7df)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8160dc0d)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8166826e)
Location: include/linux/mm.h:871
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166fce2)
Location: include/linux/mm.h:871
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bdab9)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170b211)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8170e426)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81763b22)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff81821d11)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff8182ee35)
Location: include/linux/mm.h:871
Inline: True
```
```
In net/core/sock.c (ffffffff81897cb7)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818a2869)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818ae990)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818d9715)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818e19f2)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818e4e28)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818e6b35)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81929a86)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819348d1)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81976a73)
Location: include/linux/mm.h:871
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a05b91)
Location: include/linux/mm.h:871
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
In init/do_mounts.c (ffffffff8289a75c)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/init_64.c (ffffffff81a90b35)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
```
In kernel/fork.c (ffffffff810971a3)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a05c0)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81100dae)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81101770)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8113ed43)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f6554)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120835b)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8120f447)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121670f)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812208c3)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81222171)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81224554)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81225f16)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122f240)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff812354ae)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff81238c10)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812442b3)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8124afea)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_user_pages
  - mm/gup.c:__put_user_pages_dirty
```
```
In mm/memory.c (ffffffff81256a1c)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff812575ca)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81258c07)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8126578e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8126c0b4)
Location: include/linux/mm.h:937
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127381b)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff812754f3)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277eb3)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127c937)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81280047)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812881d4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128857a)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812922f0)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a920cd)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a8929)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ac4d0)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b6a3e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ba66b)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812bbf3e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812bea47)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828db211)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812c080c)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c1a1d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1ef0)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812c25ac)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devm_memremap_pages_release
```
```
In fs/read_write.c (ffffffff812c9e36)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d3754)
Location: include/linux/mm.h:937
Inline: True
```
```
In fs/pipe.c (ffffffff812d57e7)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d8274)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812fa52e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8130530e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81310cb4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81312b5d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81317184)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81318b20)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8132a945)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81331b94)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81343581)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346f0a)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cec1)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81358431)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:937
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8138ef96)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139bdfb)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a2da1)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813a9fcc)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b3924)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813cebc7)
Location: include/linux/mm.h:937
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813d9e4a)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e3c01)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e61ae)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9e06)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fac1d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb255)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81407446)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81410a5d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff81416d1a)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81473094)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c771c)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_pc_page
```
```
In block/partition-generic.c (ffffffff814e1cf4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e4632)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4fd8)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e58cd)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e62c4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7c28)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814e9906)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814e9f75)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea1ab)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea555)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea6f4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ea9cf)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814eb9d1)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ebced)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e52e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81641dbb)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8169dce7)
Location: include/linux/mm.h:937
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816a5760)
Location: include/linux/mm.h:937
Inline: True
```
```
In drivers/base/memory.c (ffffffff816f89c7)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8174680d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81749bef)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817a18ad)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8186483d)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81871460)
Location: include/linux/mm.h:937
Inline: True
```
```
In net/core/sock.c (ffffffff818e21f4)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818ed451)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818fa27e)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8192b88f)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81930444)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8193481b)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819364fd)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8198cc87)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819985a2)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0600)
Location: include/linux/mm.h:937
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a754e0)
Location: include/linux/mm.h:937
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
In init/do_mounts.c (ffffffff8289d741)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffff8109cc83)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a6bab)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff8110d20e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff8110dba0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114a771)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff81203512)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812156cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121caeb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122401f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122e373)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8122fc21)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812322e4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81233c0e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123d3d0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff812436ee)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff81246f00)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81252773)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff812594da)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81264fac)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff81265b1a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812670d7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff812740a3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127aec4)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (ffffffff8128268b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff812842ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812879a3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128c415)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8128f4d0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81297dd4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812980ea)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a2070)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81ac985d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (ffffffff812b04db)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9ea9)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bea1c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c890e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812cc54b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812cde1e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d0877)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828e3647)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812d2759)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812d394d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3e20)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812d44ea)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812db8bb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e52e4)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (ffffffff812e7357)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e9de4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130c2ae)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8131839e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff813213be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff81325a9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8132a002)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132b960)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8133dae5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81341115)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134f8be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff813516d1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff8135b9bf)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f218)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff81365191)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81370681)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813a79f6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813b4903)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813bbc01)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813c2efc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813ccb42)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e8297)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813ef016)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813f3e8f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813fdc31)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81400211)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81403ea6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81414aed)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81415125)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142225f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8142a66d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff81430c4b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148ce34)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814e0682)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814fb0b3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814fd9f2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe54f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fec9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814ff694)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81500ff8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff81502cca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81503335)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8150356b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81503915)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503ab4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81503d8b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81504d91)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815050ad)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816608e7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8166437b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816c0a57)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816c8490)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (ffffffff8171ce37)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a95d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8176dd3f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817c686d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d334c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8189657d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818a3260)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (ffffffff819143b3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8191f544)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8192c3be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8195dbcb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81962642)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819675ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819694cd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819c3626)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819cf1a6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a17630)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25286)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
In init/do_mounts.c (ffffffff81004245)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In kernel/fork.c (ffffffff810a38c6)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810ae415)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff811183f6)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81118bc0)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8115b2c4)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8122b214)
Location: include/linux/mm.h:1058
Inline: True
```
```
In kernel/events/core.c (ffffffff81231f1c)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81246f81)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81252caf)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125a1d5)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8125cfbf)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8125e51d)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__put_page
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812613a7)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81265993)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8126f8ae)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8127476a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81282bd3)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81287bfc)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:put_compound_head
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/memory.c (ffffffff8129537c)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff81295e82)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81297201)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff812a5323)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812b47fb)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81bc5ae4)
Location: include/linux/mm.h:1058
Inline: True
```
```
In mm/madvise.c (ffffffff812b5d8e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b9963)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812bf3dc)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812c217c)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812cb497)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812cba1e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff812d6e0e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812e113e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812e33a6)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812eea7b)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f3e75)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff812fbd2c)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81301edd)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff81304135)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813072b3)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8130866f)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813096bd)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8130aa25)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff8131153a)
Location: include/linux/mm.h:1058
Inline: True
```
```
In fs/exec.c (ffffffff8131c4e4)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8131ef17)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81321fd4)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8134578a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813508ff)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8135baf5)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff8135ee4d)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81363cd3)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81365638)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81377035)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81396048)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff81398128)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff813a051a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a37d0)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff813ac2bb)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff813b7a28)
Location: include/linux/mm.h:1058
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:1058
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f3a16)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813ffdca)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8140c906)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8140f4af)
Location: include/linux/mm.h:1058
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81418a0e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff81434dfa)
Location: include/linux/mm.h:1058
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8143bd01)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff8143fa1d)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8144b697)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8144da98)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81451cf7)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81462d9a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff814633e5)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81470e96)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8147a765)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff814806c8)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff814e40ab)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8153f7b6)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8154a9fd)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff8155de2e)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff8155e132)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8155eb3b)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8155f3bb)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8155fd42)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81561bb0)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff815639c0)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff81563bad)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81563e32)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81564162)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81564367)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8156476c)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81565647)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8156598a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817105d7)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81712a36)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817744da)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8177c900)
Location: include/linux/mm.h:1058
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182caef)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81830304)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8188d007)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff81963f39)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff8197245a)
Location: include/linux/mm.h:1058
Inline: True
```
```
In net/core/sock.c (ffffffff819e63ce)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819f2696)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff8ce)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a2cccb)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a35e88)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3ab28)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a3cf06)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81aaed2a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81abc08a)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08614)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16eb6)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b225c0)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81baae98)
Location: include/linux/mm.h:1058
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
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
In init/do_mounts.c (ffffffff81bd187b)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810660b6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066e92)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810a9a2c)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81bdf88d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81114690)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811573fe)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8123314e)
Location: include/linux/mm.h:1099
Inline: True
```
```
In kernel/events/core.c (ffffffff8123bb88)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812515cd)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125d87f)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:generic_file_buffered_read_readpage
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81264335)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8126731b)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812685dd)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8126b7a7)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81270370)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8127ac1e)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8127efbd)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8128d042)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81291bb6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a01b2)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a11b9)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a21b6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff812b07fc)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812c01b5)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81c3eaca)
Location: include/linux/mm.h:1099
Inline: True
```
```
In mm/madvise.c (ffffffff812c3051)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c53cc)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812cafd6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812cde6e)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812d70b7)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812d73be)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff812e299e)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff812eb9e2)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812ee821)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812fa0eb)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff765)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff81307979)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130edbb)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff8130fd7e)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_isolation.c:set_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81312ff3)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff81314443)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813154cd)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff81316905)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pageunmap_range
```
```
In fs/exec.c (ffffffff813279c4)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8132a447)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8132d594)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81351ec8)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8135d8cf)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff813668ba)
Location: include/linux/mm.h:1099
Inline: True
```
```
In fs/buffer.c (ffffffff8136a0a5)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff8136c62d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81370e37)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff81372508)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81384c3c)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813a7d68)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff813a99a5)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff813b9650)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bd8a5)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff813c94b8)
Location: include/linux/mm.h:1099
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814061a6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814125c9)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff8141fd73)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8142296b)
Location: include/linux/mm.h:1099
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c417)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8144d8da)
Location: include/linux/mm.h:1099
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81458080)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff8145baed)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff81467d77)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146a058)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e21c)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e83a)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ec35)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148b769)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8149546d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff8149bdab)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff815014d2)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8155bfce)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8156682c)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81579c3d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81579d92)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8157a772)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8157af6d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8157b85c)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8157d680)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8157eaee)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8157ecdd)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8157ef62)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8157f27d)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8157f4a7)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8157f889)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815805e7)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8158091a)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d1b7)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8172f7c6)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8178f23a)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81795a50)
Location: include/linux/mm.h:1099
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183dc20)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81840f7b)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8189b279)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff8196a828)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81977367)
Location: include/linux/mm.h:1099
Inline: True
```
```
In net/core/sock.c (ffffffff819e5be4)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819f2696)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819ff62e)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a2e284)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a37d78)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3ce04)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a3e3b8)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81ab8f8b)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac77ca)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16b74)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25126)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b30fc0)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81bbb23b)
Location: include/linux/mm.h:1099
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
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
In init/do_mounts.c (ffffffff81bc388b)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066513)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106743e)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810aaa5d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81bd17b0)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81114e50)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81158812)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8124021d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81257bb8)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812606d7)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81269f15)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8126ba94)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8126df6d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81270337)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8127611c)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8127fd9b)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8128413d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81291b76)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff812974a6)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a5aef)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff812a6e1a)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a7a46)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff812b5e27)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812c5925)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__putback_isolated_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/shuffle.c (ffffffff81c30b99)
Location: include/linux/mm.h:1124
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812c664e)
Location: include/linux/mm.h:1124
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
In mm/madvise.c (ffffffff812c9ec2)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cc083)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d1ab4)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812d51b0)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812de6ae)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812deb6e)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812ea12e)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812f49b1)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81300e96)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81306502)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff8130e0fb)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81315159)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff81315ed3)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff81319238)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8131b38c)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff8131bb9d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8131cb55)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff8132d7a5)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813303e7)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81332f34)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81358bec)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81364362)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff8136d16a)
Location: include/linux/mm.h:1124
Inline: True
```
```
In fs/buffer.c (ffffffff81371361)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff81372f5d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff813777e4)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813785e8)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff8138b729)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813aedca)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff813b0705)
Location: include/linux/mm.h:1124
Inline: True
```
```
In fs/verity/verify.c (ffffffff813b0ee9)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff813c07c5)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c49f1)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff813d0595)
Location: include/linux/mm.h:1124
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140c685)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418a38)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814209da)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81429178)
Location: include/linux/mm.h:1124
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433112)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814533d6)
Location: include/linux/mm.h:1124
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8145da38)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff8146142d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8146d376)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146f8c1)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81473660)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff814843cc)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81484788)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81490741)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8149a4cd)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff814a0ec5)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81507fb2)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff815639dc)
Location: include/linux/mm.h:1124
Inline: True
```
```
In block/blk-map.c (ffffffff8156ed6d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81581970)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81581ac2)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815824a2)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81582c9d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff81583563)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81585210)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff815865df)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8158683d)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81586abe)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81586ddf)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81586fe7)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815873c9)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81588157)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8158848a)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff815eff57)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710f27)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8171382b)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81772027)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81778710)
Location: include/linux/mm.h:1124
Inline: True
```
```
In drivers/base/memory.c (ffffffff817d20a7)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820db0)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8182416b)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8187dad6)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff8194e638)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff8195ba77)
Location: include/linux/mm.h:1124
Inline: True
```
```
In net/core/sock.c (ffffffff819cbcf4)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819d88c3)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819e5d9f)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a14f3b)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a1ef0c)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a23bc4)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81a4dae4)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/ipv4/tcp.c (ffffffff81aa423e)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab27da)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0488f)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12d46)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b1ecee)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81baa87e)
Location: include/linux/mm.h:1124
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In init/do_mounts.c (ffffffff81c948ee)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070631)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810717c9)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810bc581)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81caa406)
Location: include/linux/mm.h:1128
Inline: True
```
```
In kernel/power/swap.c (ffffffff811354e8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8117d71c)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8127ac2c)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff8129126d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129d0c8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:end_page_private_2
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6ba5)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812a8761)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/swap.c (ffffffff812aaeba)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812ad5d9)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b2775)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff812be0a8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff812c28e8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff812d18d0)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff812d7e53)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812dd0ec)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memory.c:put_page
```
```
In mm/mincore.c (ffffffff812e82ef)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812e9066)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff812f9ab7)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8130a023)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
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
In mm/shuffle.c (ffffffff81d4f4bf)
Location: include/linux/mm.h:1128
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130afb2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/madvise.c (ffffffff8130eee2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8131126a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8131724f)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff8131a7cc)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff813259df)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8132609d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff81332050)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8133f151)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134ab0d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81350289)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff81358f13)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813611ef)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff81361fd8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8136590f)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff8136684e)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff81368482)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff81368e5a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff81369ea5)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff8137afd2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8137dba4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff813806c1)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813a72d9)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813b2b77)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff813bbe47)
Location: include/linux/mm.h:1128
Inline: True
```
```
In fs/buffer.c (ffffffff813bfca2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff813c3ec3)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813c4ec8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff813d8cd9)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813fe96a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff814002ef)
Location: include/linux/mm.h:1128
Inline: True
```
```
In fs/verity/verify.c (ffffffff81400b6a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff8141062e)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff814141a4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81421d44)
Location: include/linux/mm.h:1128
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145f239)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146bc39)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81473d9c)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8147cf71)
Location: include/linux/mm.h:1128
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486a90)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814a73b3)
Location: include/linux/mm.h:1128
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b2ef5)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff814b691a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff814c3bfc)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814c632b)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca258)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff814dba49)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbe08)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e81ce)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814f1f3a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff814f8eea)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81565232)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff815c538a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff815c8b68)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff815d33a8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff815e6d6e)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff815e6ed2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815e77fc)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e801d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815e8e50)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff815eab6d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff815ec06c)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff815ec38a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815ec5fa)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815ec921)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815ecb64)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815ecf32)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815eddf4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815ee12a)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff8165d1f2)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178da39)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff817910df)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817f7dc4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817fe5bd)
Location: include/linux/mm.h:1128
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab790)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff818af9a8)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8190f199)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff819f3a3b)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81a0126d)
Location: include/linux/mm.h:1128
Inline: True
```
```
In net/core/sock.c (ffffffff81a7b354)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81a887f5)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a97f9b)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81ac8853)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81ad2fac)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad824d)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81b06381)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/ipv4/tcp.c (ffffffff81b60515)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f6c4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6bec)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6c41)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81be395c)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81c7e721)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In init/do_mounts.c (ffffffff81e43aa2)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dba7)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f873)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810d32bc)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81e5a820)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81157a18)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811b28fb)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff812cdc1e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e6810)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f3631)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/page-writeback.c (ffffffff812ff0bf)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/readahead.c (ffffffff81301a82)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff813032f7)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__put_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308085)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff8130f535)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8131996e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/vmstat.c (ffffffff8131f9c4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81330c9a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff813379c5)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_get_folio
```
```
In mm/memory.c (ffffffff813481b4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:copy_present_pte
```
```
In mm/mincore.c (ffffffff8134967e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff8134c255)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/rmap.c (ffffffff8135f556)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81372d63)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
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
In mm/shuffle.c (ffffffff81f1f41d)
Location: include/linux/mm.h:1095
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff813746a2)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/madvise.c (ffffffff81376de4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c2e1)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81382a27)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81385d53)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff813946b4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81395160)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff813a3461)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b6032)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6399)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1b0e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c84ef)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff813d321a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd51b)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff813dea47)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff813e1dcb)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813e3b3e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5c0b)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff813e67e2)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff813e72d7)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff813fb2a8)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe426)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814006e3)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c832)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81437bf5)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81446946)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff8144ad30)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8144bcf5)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81464832)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff814724b3)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff8147408b)
Location: include/linux/mm.h:1095
Inline: True
```
```
In fs/verity/verify.c (ffffffff81474b61)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff8148612d)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/proc/task_mmu.c (ffffffff8149a2e3)
Location: include/linux/mm.h:1095
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814ddb3b)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814e3f9e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff814f5561)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff814ff7ba)
Location: include/linux/mm.h:1095
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a391)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153c6b4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff8154e85e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81551369)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555f9a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8156965e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81569aba)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81577154)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8157f88f)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff81589568)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81600a58)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff816704b9)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff81673c90)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8167f11d)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81695f70)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff8169613c)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c34)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff816975fd)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff8169863e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a6a3)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8169c1a4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8169c60a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c952)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169ce71)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169d02e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d473)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e482)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e875)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff8177668e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61f3)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c8df6)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81936b53)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193dbb8)
Location: include/linux/mm.h:1095
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e92)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81a63e9e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81b5d6c9)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81b68d42)
Location: include/linux/mm.h:1095
Inline: True
```
```
In net/core/sock.c (ffffffff81bed2ed)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81bfdff2)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/filter.c (ffffffff81c44e4f)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c51a0b)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c5398a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81c59035)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81c8c12e)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81ceee36)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cfeda2)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c3e4)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d82b)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b3f7)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81e1d78a)
Location: include/linux/mm.h:1095
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
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
In init/do_mounts.c (ffffffff83e623af)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f113)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109193d)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810f1ddb)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81185c9a)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81188916)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/dma/mapping.c (ffffffff811c12cb)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c2f53)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/futex/core.c (ffffffff811f379b)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff813391b7)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813502f4)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
```
```
In mm/filemap.c (ffffffff8135d96d)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/page-writeback.c (ffffffff81369747)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/readahead.c (ffffffff8136c1aa)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff8136f793)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff81372035)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff8137e82f)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff8138cc99)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/vmstat.c (ffffffff81393574)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813a7c24)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff813b1eeb)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813c0670)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813c526b)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/mprotect.c (ffffffff813ce090)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813da396)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff813f04e3)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
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
In mm/shuffle.c (ffffffff820c8646)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff813f1812)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/madvise.c (ffffffff813f422d)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f9a81)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc976)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff81403b2e)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff814130fd)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81414d00)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8142318d)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81436186)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff814388b1)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443c6f)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81449c16)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81458934)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81464153)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff81465707)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff814693ae)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff8146b51b)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d91a)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e2e2)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8146ef42)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff81485363)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814880a6)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8148a8b3)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ba0a2)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814c5f29)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff814d5a45)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff814d9302)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814f23d9)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81503fd1)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062de)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506ea3)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff815199b6)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/proc/task_mmu.c (ffffffff8152de74)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In fs/ext4/inline.c (ffffffff81576b80)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8157d57e)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff81590f7b)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81599f66)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4ede)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815dad81)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff815eee45)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f24c0)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7692)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d257)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d6e4)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b834)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8162554d)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff8162f8a2)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816b19bf)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8172b859)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8172f6d6)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_try_merge_page
```
```
In block/blk-map.c (ffffffff8173c1d7)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In lib/scatterlist.c (ffffffff817ced8c)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - lib/scatterlist.c:pages_are_mergeable
  - lib/scatterlist.c:pages_are_mergeable
```
```
In drivers/pci/p2pdma.c (ffffffff8191bef7)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16b23)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a1a18e)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a969f3)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9eae8)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5f6c)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7345f)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81bf3051)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81cf7638)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d04862)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In net/core/sock.c (ffffffff81d99578)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81da503c)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/filter.c (ffffffff81dff3a3)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e06dd0)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e09119)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e0ef95)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81e47380)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81eb205c)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3baa)
Location: include/linux/mmzone.h:973
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26551)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38dfb)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f48441)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81ff4f0c)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f0b8)
Location: include/linux/mmzone.h:973
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffffffff8368288b)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092013)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109487a)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810fdd4c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff81196e6a)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81199ad3)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/dma/mapping.c (ffffffff811d3d4b)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5a93)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/futex/core.c (ffffffff81207f80)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8136a7bb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813814dc)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
```
```
In mm/page-writeback.c (ffffffff8139b8e4)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813a18b3)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813a41d7)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff813aff16)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813bec60)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/vmstat.c (ffffffff813c5ef4)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff813db082)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff813e6c8b)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813f53fb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f9690)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff8140292f)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140ead6)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81424073)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
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
In mm/shuffle.c (ffffffff8214c8c6)
Location: include/linux/mmzone.h:1084
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81425352)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/madvise.c (ffffffff814278b3)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c98c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fd0f)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff814376c3)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81440e2b)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff81448290)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff814581ab)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8146bd8b)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146e5b1)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147914a)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ff2f)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8148e557)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81499c19)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff8149b187)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff8149e33d)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a0304)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/memremap.c (ffffffff814a371e)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff814ba3d0)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf75)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a61)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ef020)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814fb413)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8150a980)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff8152901d)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff8153d615)
Location: include/linux/mmzone.h:1084
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153e249)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815512aa)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/proc/task_mmu.c (ffffffff815661eb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In fs/ext4/mballoc.c (ffffffff815c64c0)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/squashfs/block.c (ffffffff816242cf)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626e1d)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a5af)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162fb80)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81645117)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff816455a1)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff816539a8)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d8bd)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff81667b01)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816ea37e)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817676bb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff817691e5)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - block/bio.c:bvec_try_merge_page
  - block/bio.c:bvec_try_merge_page
```
```
In lib/scatterlist.c (ffffffff8180d23c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - lib/scatterlist.c:pages_are_mergeable
  - lib/scatterlist.c:pages_are_mergeable
```
```
In drivers/pci/p2pdma.c (ffffffff8195f50a)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fbb3)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a62cdb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae2205)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aea45a)
Location: include/linux/mmzone.h:1084
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b246ec)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d95)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81c4a2ab)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c5424c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/md/md.c (ffffffff81d5ef2c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d922)
Location: include/linux/mmzone.h:1084
Inline: True
```
```
In net/core/sock.c (ffffffff81e07898)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81e1ecf5)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/filter.c (ffffffff81e70e73)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79711)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b788)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e82755)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
```
In net/core/skmsg.c (ffffffff81ea2de8)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81f1070c)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f22db7)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f861df)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98aed)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa8003)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82071702)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f0cb)
Location: include/linux/mmzone.h:1084
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
In init/do_mounts.c (ffffffff838b192b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099383)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd5a)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff81106a34)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff811a591b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff811a8b33)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/dma/mapping.c (ffffffff811e89eb)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811eaa13)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/events/core.c (ffffffff8139314b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813aa88b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
```
```
In mm/page-writeback.c (ffffffff813c430d)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/swap.c (ffffffff813cb539)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
  - mm/swap.c:__folio_put
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
  - mm/swap.c:lru_gen_add_folio
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/truncate.c (ffffffff813cdd27)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff813d9401)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:update_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:lru_gen_add_folio
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813e9c94)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/vmstat.c (ffffffff813f08f4)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8140520c)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8141191b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81415b45)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff8142523b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
```
In mm/mprotect.c (ffffffff8142ef61)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143b496)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450f12)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
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
In mm/shuffle.c (ffffffff8222f3d6)
Location: include/linux/mmzone.h:1094
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81452592)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_deinit_memmap_on_memory
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/madvise.c (ffffffff81461091)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81465672)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff814697e9)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/hugetlb.c (ffffffff8147af55)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff81485ae0)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81491f35)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81496ee9)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149ef3a)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a886c)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814adb04)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814bddc9)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c9408)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:__add_to_kill
  - mm/memory-failure.c:page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
  - mm/memory-failure.c:__page_handle_poison
```
```
In mm/page_isolation.c (ffffffff814ca867)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff814cd46f)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/memremap.c (ffffffff814d45be)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff814ec950)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef415)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f30ad)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/splice.c (ffffffff81530102)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8153f4d0)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff8155def7)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff81572a75)
Location: include/linux/mmzone.h:1094
Inline: True
```
```
In fs/verity/verify.c (ffffffff815737e3)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81587162)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/proc/task_mmu.c (ffffffff8159e1dd)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In fs/ext4/mballoc.c (ffffffff81601e77)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/squashfs/block.c (ffffffff8165d36c)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff7e)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff816638d9)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e644)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8167ea96)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168cfb8)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff816975fd)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
```
```
In fs/fuse/readdir.c (ffffffff816a1e37)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff8172708e)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817a94a7)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff817ab2d5)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - block/bio.c:bvec_try_merge_page
  - block/bio.c:bvec_try_merge_page
```
```
In lib/scatterlist.c (ffffffff81852eec)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - lib/scatterlist.c:pages_are_mergeable
  - lib/scatterlist.c:pages_are_mergeable
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b6a)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab23c3)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab530b)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b355f5)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3d8e7)
Location: include/linux/mmzone.h:1094
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b35c)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b904)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81cffc34)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d078ff)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_receive_page_frags
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:virtnet_rq_unmap
  - drivers/net/virtio_net.c:page_to_skb
```
```
In drivers/md/md.c (ffffffff81e1619c)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81e24d5f)
Location: include/linux/mmzone.h:1094
Inline: True
```
```
In net/core/sock.c (ffffffff81ec42d8)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81edc355)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/filter.c (ffffffff81f30547)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f397e1)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3ba18)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81f436e5)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f65118)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81fd48f8)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7c47)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d7bf)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065e5d)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff820752c3)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82145882)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff821770cb)
Location: include/linux/mmzone.h:1094
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
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
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/swap.c (ffff8000102c10e8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102ce7cc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffff8000102d3828)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffff8000102da2a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffff8000102eb314)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffff8000102fe2a8)
Location: include/linux/mm.h:950
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
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/hugetlb.c (ffff80001032e7d8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff800010336f34)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/memory_hotplug.c (ffff800010d9c908)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/migrate.c (ffff800010353008)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035a1ac)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/khugepaged.c (ffff80001035df2c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff80001036b858)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffff80001036de94)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In mm/page_isolation.c (ffff8000103722a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffff800010375c8c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffff80001145cb80)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b040)
Location: include/linux/mm.h:950
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
In arch/arm/mm/fault.c (c031a690)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:show_pte
```
```
In arch/arm/mm/dma-mapping.c (c031ae84)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:dma_cache_maint_page
  - arch/arm/mm/dma-mapping.c:cma_allocator_free
  - arch/arm/mm/dma-mapping.c:__alloc_from_contiguous
  - arch/arm/mm/dma-mapping.c:__dma_clear_buffer
```
```
In arch/arm/mm/flush.c (c031eb08)
Location: include/linux/mm.h:950
Inline: True
```
```
In arch/arm/mm/highmem.c (c0321cec)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
  - arch/arm/mm/highmem.c:kmap
```
```
In kernel/fork.c (c0350194)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/power/snapshot.c (c03bf448)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:preallocate_image_pages
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
```
```
In kernel/dma/direct.c (c03e1cdc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
```
In kernel/kexec_core.c (c040fa58)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/iomem.c (c04d8e94)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/swap.c (c04ed3ec)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f85b4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (c04fbb80)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/mmzone.c (c05005ac)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mmzone.c:memmap_valid_within
```
```
In mm/vmstat.c (c0501124)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (c050e95c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (c05140a8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/highmem.c (c0515eec)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/highmem.c:set_page_address
```
```
In mm/memory.c (c051bba4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/mlock.c (c051d300)
Location: include/linux/mm.h:950
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
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/migrate.c (c0550ed4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c055cee8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/page_isolation.c (c055ef90)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (c0561f60)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (c1534ea4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In fs/buffer.c (c05b1b54)
Location: include/linux/mm.h:950
Inline: True
```
```
In crypto/skcipher.c (c076c8dc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In drivers/virtio/virtio_balloon.c (c0947544)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/usb/core/message.c (c0af97a8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/edac/edac_mc.c (c0bedea8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (c0ccf204)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (c0ce49c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
  - net/core/dev.c:netif_skb_features
```
```
In net/xdp/xdp_umem.c (c0e7bba4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_unmap_pages
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
In init/do_mounts.c (c000000001344c4c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0f50)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In kernel/fork.c (c000000000136cb8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (c000000000144a3c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/futex.c (c00000000021d1c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (c000000000337d50)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000350b30)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (c00000000035bd10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c000000000367640)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (c000000000375e50)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c0000000003780e0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c00000000037c184)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (c00000000037e8a0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c00000000038c5e0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (c000000000395910)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (c00000000039ab1c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (c0000000003ac8a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (c0000000003b78c4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c6ec0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (c0000000003c7cb0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c0000000003c9b1c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (c0000000003d96c8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (c0000000003e3300)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (c0000000003ee3f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c0000000003f2950)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f8040)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fea80)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c000000000404310)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (c000000000410aa0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c0000000004112b4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (c00000000041f000)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (c000000000430778)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (c0000000004367f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c0000000004442d0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c00000000044b4b0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000045b380)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c000000000461c88)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (c000000000463bb0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (c000000000468674)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (c000000001387184)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (c00000000046af00)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c9a0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046d180)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (c00000000046dd90)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (c0000000004773e0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/exec.c (c000000000484d80)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (c0000000004879a0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c00000000048c870)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c0000000004bf230)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (c0000000004d1880)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (c0000000004de9c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (c0000000004e5010)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (c0000000004eb7b0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ed4d0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (c000000000504ef0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c00000000050ac60)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (c00000000051edf0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c0000000005216c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c0000000005300a0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c000000000533cb0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (c00000000053d060)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (c00000000054dd9c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (c00000000059e660)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c0000000005afe30)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (c0000000005bac10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (c0000000005c4fc8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (c0000000005d1fcc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f78d0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (c0000000006009b0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (c0000000006081f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c000000000616f10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619f90)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (c00000000061f780)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (c0000000006371d0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c000000000637780)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c00000000064a220)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c0000000006557a0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (c00000000065e060)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0000000006edc40)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (c00000000076e848)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (c000000000796740)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c000000000799770)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a6c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079b120)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bf10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c00000000079e9c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c0000000007a0890)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c0000000007a0fd0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a13c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1874)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1b30)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1f30)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a3440)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a3900)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d660c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (c00000000094bd40)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (c000000000955d60)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (c0000000009b1b64)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25450)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c000000000a29fa0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (c000000000aa36f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2d60)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
```
```
In drivers/md/md.c (c000000000bd7410)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (c000000000be4ee0)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (c000000000c807f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c000000000c92830)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (c000000000ca5110)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (c000000000ce9900)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c000000000cf1750)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c000000000cf8570)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c000000000cfb530)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (c000000000d7dcc0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d8ce10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (c000000000df1c94)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (c000000000e05790)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/swap.c (ffffffe0001e3618)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ec92c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffe0001ef914)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/vmstat.c (ffffffe0001f45a8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffe0001ff78a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/mlock.c (ffffffe00020c86e)
Location: include/linux/mm.h:950
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
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:is_free_buddy_page
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
In mm/hugetlb.c (ffffffe00022c818)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffe00023e9e6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000248e84)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/page_isolation.c (ffffffe00024b4f8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffe00024e410)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/cma.c (ffffffe000019b4a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fc72)
Location: include/linux/mm.h:950
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
In init/do_mounts.c (ffffffff8288b741)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffff810965a3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a04cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff8110542e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81105db5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81142d91)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811fbb32)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120dd1b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121513b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c66f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812269c3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81228271)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8122a934)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8122c25e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81235a20)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8123bd3e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8123f550)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8124adc3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81251b2a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d5fc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8125e16a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125f727)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8126c6f3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81273514)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127acdb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127c91a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127ff3b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812849f5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81287ab0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812903b4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812906ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8129a650)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a686cd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (ffffffff812a8abb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b2489)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b6ffc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c0eee)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c4b2b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812c63fe)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c8e57)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828cc4fb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812cad39)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812cbf2d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc400)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ccaca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d3e9b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd8c4)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (ffffffff812df937)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e23c4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130488e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8131097e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8131999e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131e07d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff813225e2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81323f40)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff813360c5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff813396f5)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (ffffffff81347e9e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81349cb1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81353f9f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813577f8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135d771)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81368c61)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139ffd6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813acee3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b41e1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813bb4dc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c5122)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e0877)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e75f6)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ec46f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f6211)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f87f1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc486)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d0cd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d705)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141a83f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81422c4d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff8142922b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81485414)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d8c62)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814f3693)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f5fd2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f6b2f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f727d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f7c74)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f95d8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814fb2aa)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814fb915)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fbb4b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbef5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fc094)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fc36b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814fd371)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd68d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626757)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8162a1eb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816864a7)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8168dee0)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (ffffffff816e3167)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f04d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8172242f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8178b34d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8183c3fd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818490e0)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (ffffffff818b43b3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818bf544)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818cc3be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818fdb9b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81902612)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8190759a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8190949d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81963496)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8196f016)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b6cc0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4916)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
In init/do_mounts.c (ffffffff828896be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffff81085023)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8108eeef)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff810f66ce)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff810f7060)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811360f1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811ee87d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81200aeb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81207eab)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f853)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81219b33)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8121b3b1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8121da54)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff8121f338)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81228a8a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8122ed3e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff81232550)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff8123dd63)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff81244c7f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124fa4c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812505fa)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81251b47)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8125e755)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81265484)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126cbbb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8126e7ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271e12)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81276865)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81279910)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81282044)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128234a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8128c210)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a2518d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (ffffffff8129a47b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a3815)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a81cc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812b1f42)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b5b6b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812b743e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812b9e97)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828c4c17)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812bbca0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812bcd9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd270)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812bd93a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812c4b1b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce544)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (ffffffff812d0577)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d3004)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812f54ae)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8130158e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8130a55e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8130ec1d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81313182)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81314ae0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81326db5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8132a425)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (ffffffff81338b7e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8133a991)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81344c5f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813484a8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134e411)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81359f1f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81390a66)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139d973)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813a4c71)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813abf6c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b5ba2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813d12f7)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813d8076)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813dceef)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e6c91)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e9271)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecf06)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdb4d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe185)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140b2bf)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814136cd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff81419cab)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81475e34)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c9612)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814e3ba3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e64e2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e703f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e778d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e8184)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9ae8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814eb7ba)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814ebe25)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ec05b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec405)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec5a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ec87b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814ed881)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814edb9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161add7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816643d3)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166b8d0)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bd7a7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f847d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff816fb85f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8176ac9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d3fc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff81803a5d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81810740)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (ffffffff8186e303)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81879484)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8188644e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b79cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818bc442)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818c13aa)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818c32ad)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8191cf86)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81928b06)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81973ab0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81981706)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
In init/do_mounts.c (ffffffff8289e741)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffff81096553)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a047b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff811036de)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff81104070)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81140c41)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f9902)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120babb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81212edb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a40f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81224763)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81226011)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812286d4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81229ffe)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812337c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff81239ade)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8123d2f0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81248b63)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8124f8ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b39c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8125bf0a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125d4c7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff8126a493)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812712b4)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (ffffffff81278a7b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127a6ba)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127dd93)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81282805)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812858c0)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128e1c4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128e4da)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81298460)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81ad4add)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (ffffffff812a68cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b0299)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4e0c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812becfe)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c293b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812c420e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812c6c67)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828df27b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812c8b49)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c9d3d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca210)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ca8da)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d1cab)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db6d4)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (ffffffff812dd747)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e01d4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130267e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8130e76e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8131746e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8131bb4d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff813200b2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81321a10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81333b95)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff813371c5)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134596e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81347781)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81351a6f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813552c8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135b241)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81366731)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8139d836)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813aa743)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813b1a41)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813b8d3c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c25b2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ddbf7)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e4976)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813e97ef)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f3591)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f5b71)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9806)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a44d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140aa85)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814169df)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8141eded)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff814253cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814814b4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d4cf2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814ef723)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f2062)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2bbf)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f330d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f3d04)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f5668)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff814f733a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff814f79a5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7bdb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7f85)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f8124)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f83fb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814f9401)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f971d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654727)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff816581bb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816b4b23)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816bc150)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (ffffffff817102f7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175de1d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff817611ff)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817bb6ed)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c81cc)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8188ba2d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81898710)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (ffffffff819053b3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81910544)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8191d3be)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8194ebcb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81953642)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819585ca)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8195a4cd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819cdc66)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d97e6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a21740)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f396)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
In init/do_mounts.c (ffffffff8289e746)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffff8109e133)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a8406)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/snapshot.c (ffffffff8110eace)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/power/swap.c (ffffffff8110f460)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114de9c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff812083b6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8121a8cb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81221e4a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812294da)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81233a33)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81235311)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81237a44)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:lru_cache_add_active_or_unevictable
  - mm/swap.c:put_pages_list
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff812393eb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81242cf7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff812491ce)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/vmstat.c (ffffffff8124ca20)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
```
```
In mm/compaction.c (ffffffff81258394)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8125f24e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126ad61)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff8126b8fa)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8126cead)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/rmap.c (ffffffff81279dfe)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81280d24)
Location: include/linux/mm.h:950
Inline: True
```
```
In mm/page_alloc.c (ffffffff8128866b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
  - mm/page_alloc.c:is_free_buddy_page
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8128a29a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d943)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812924ec)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81294eef)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129df62)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129e3d1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a8183)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81ae0fbd)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
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
In mm/migrate.c (ffffffff812b6bfb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812c05d9)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c4c2e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812cf77e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d33db)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:add_to_kill
```
```
In mm/page_isolation.c (ffffffff812d4cce)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
```
```
In mm/zsmalloc.c (ffffffff812d72c5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/cma.c (ffffffff828e4692)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/userfaultfd.c (ffffffff812d983a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812daa38)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812daf10)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812db602)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812e2ae6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec668)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/pipe.c (ffffffff812ee6c7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812f1ab4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81313c9e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8131ff6e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8132905e)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffff8132d92d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81331dd2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81333770)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81345c03)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8134a285)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/verity/enable.c (ffffffff81358c49)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8135aa81)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff8136500a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813688a3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8136e9a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff81379a6f)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b1da6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813bf064)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffff813c658a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff813cda5c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813d779a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813f3017)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813f9dba)
Location: include/linux/mm.h:950
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ff100)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff814091a1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8140b7c1)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f461)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81420151)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8142071b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142d73f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81435b4d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/readdir.c (ffffffff8143c295)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81499038)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814ed8a2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff815087b3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8150b0c2)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150bc1f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150c36d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8150cd64)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e6c8)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffff8151039a)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffff81510a05)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510c3b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510fe5)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81511184)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8151145b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81512461)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8151277d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f1a7)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff816727bb)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816cedf7)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816d6a40)
Location: include/linux/mm.h:950
Inline: True
```
```
In drivers/base/memory.c (ffffffff8172b457)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8177947d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8177c85f)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817d4728)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e246c)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff818aac9d)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818b5770)
Location: include/linux/mm.h:950
Inline: True
```
```
In net/core/sock.c (ffffffff819264a3)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819316a4)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8193e8de)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8197059b)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81975168)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8197a6fa)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197c6ed)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819d77f6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e3446)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2ca90)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ace6)
Location: include/linux/mm.h:950
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
</details>
</li>
</ul>

## Differences
