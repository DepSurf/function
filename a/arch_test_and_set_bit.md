# Function: <code>arch_test_and_set_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a19b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016e0b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024f65)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c5cb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff810321bf)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103d81d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046ad3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81060f7e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/softirq.c (ffffffff810a1115)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b8b95)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c0166)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a98c1f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110a37a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81116cc1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c548)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113dca9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8113ecc9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff811783dc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/watchdog.c (ffffffff81183e4b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81184912)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811f4e42)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8120f328)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81216494)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff8121b253)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8121eb53)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81221d96)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In mm/swap.c (ffffffff81224da5)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81225a09)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122e335)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812330fb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8123a8cd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In mm/gup.c (ffffffff8124bad0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ee94)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81258a68)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125a0ee)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In mm/rmap.c (ffffffff81266aa1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff81273897)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a9588a)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff81275876)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812768c7)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127734d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127bbea)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128754d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81291740)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81298258)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8129fa3d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a7f75)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812aae9e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812b2a31)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812ba4d8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812bde65)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812bfd11)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c17ae)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In fs/read_write.c (ffffffff812c9bed)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d552c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812e65c6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff812fd055)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff8130347e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130fdf3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134750d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8134b3bf)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff8134e2f1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff8134f769)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff813764f0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137ca04)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8138801d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138a799)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138dc46)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139c291)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a8974)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813b23cd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b47e1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813c7ae1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d2581)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813d81fb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d8d27)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dae6e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dc459)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e15a0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813e91cb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa948)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81406a75)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8140d9d9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8141cf79)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff8142afcb)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81435921)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d9b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149addf)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a2685)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In block/blk-core.c (ffffffff814c9078)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814db171)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814f1b7b)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff814fa7a8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff8150d606)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8153981f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8153adfc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8154a511)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81556a01)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a229e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828efd33)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815c4ab8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e365)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8166813e)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff816698f5)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816760f8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81679521)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816abecc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816b7296)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816d2e83)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/node.c (ffffffff816f8020)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_memory_block_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff81732e67)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81738f04)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8174249f)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744b0d)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c479)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e815)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_logging.c (ffffffff81758325)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff81777fad)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff8179ebd8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817b8064)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817bc9c1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817d09b6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fe0f2)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181c07c)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81836ce3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c460)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f362)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d1d0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81870c15)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188f117)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818fa7c3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff8191f8d7)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff819307a3)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In net/core/netpoll.c (ffffffff81937bd2)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff81956925)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819629cc)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969ca1)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81998af0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f1c4)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a42dd)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfaa0)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819db937)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98f8)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff819f47c6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39cd9)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81a44111)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5d6)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a7b961)
Location: arch/x86/include/asm/bitops.h:137
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100a58b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025545)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce9b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032a7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103dfdd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047253)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810617ee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a4570)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810a76d5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810bf0b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c6526)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81ad056f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111674a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81123091)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81148158)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114985c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8114a6f3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8118425c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff8118fcc4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81190792)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff81201e52)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff8121c805)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81223da4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff81228d13)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8122c5f3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8122f846)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff81232b35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81233859)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123c4c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8124131b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff81248bdd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff81259fc0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d474)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81266f38)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8126859e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff812753c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff81282707)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81acd16d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff81284846)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812863b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81286e2d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128b6ca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129715d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a14c0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a80b8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812aff79)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9460)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812bc5c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812c4470)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812cbc08)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812cfd55)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812d1c61)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812d36de)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff812db6c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812e709c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812f8126)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff8130f545)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff813164fe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81322dc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135f67d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136366f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff813665e1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff81367a79)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff8138e760)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81395104)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a09e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813a31e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813a66a6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b4da1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c1884)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813cb471)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813cd6e1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813e0ea1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813ebc61)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813f22db)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2d17)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4ebe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813f64a9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813fb5f0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8140326b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81405639)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408939)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81414818)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8141ff45)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81426bd9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81436dc9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff81444d1b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff8144f6c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c4b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814b501f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bd355)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-core.c (ffffffff814e2268)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814f45a1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8150b15b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81518708)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff8152b456)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8155a63f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8155bc1c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8156a3a1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81578021)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c311e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828f8ea4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815e5cf8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660845)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168a88e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8168be15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81698898)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff8169bd01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816cec4c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816d9e46)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816f6d63)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81756a73)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8175cc50)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817664ae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768c4d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff817705f9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817729c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8179beed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817c2668)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817e8835)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817ed1e1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818018d2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182ef42)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d43c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81868653)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186de04)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870d02)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188efc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff818a2a05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c10f7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8192c903)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81951b17)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff81962cac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963ec4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/netpoll.c (ffffffff8196aa92)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8198cdc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819a0711)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff819cf60f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5d74)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819daefd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06630)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a12867)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2160d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b476)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70869)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ad01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a86266)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81ab2cc1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100b6fb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019349)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029520)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ee4c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff82ccf1c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810410ad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a079)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810675ef)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810ab840)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810aede5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c62b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff810ce586)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81bc8eef)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81122374)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811261c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112f6c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81157f98)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81159660)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/futex.c (ffffffff8115b247)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff811982dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff811a488e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811a533d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff81229266)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81245a7b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_take_insn_slot
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81252c4b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/oom_kill.c (ffffffff81256bba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81259f03)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8125c946)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff81260017)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81260f7e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8126ad2e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126db71)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff812768ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff812884e0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128bede)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812971af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81298b5e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff812a6835)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff812b486d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81bc5b62)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff812b69f1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812b87ad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812b93ac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812be5ac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812ca755)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
```
```
In mm/ksm.c (ffffffff812d63d4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812dd2e6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812e39f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812edfc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812f198a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812fa339)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81302660)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81306856)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff81307b92)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81309192)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff81311676)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/pipe.c (ffffffff8131e877)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81330e86)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff8134eca2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/splice.c (ffffffff8135062e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/buffer.c (ffffffff8135d833)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io_uring.c (ffffffff81388d89)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffff813a5259)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813aa480)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff813ae152)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff813b1eba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/balloc.c (ffffffff813d9f1b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ddd6c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813eccb1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ef3cc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813f257a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81400231)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dbe1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81419b3d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8142da73)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81438e49)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff8143f460)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81440921)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff81442214)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81443a39)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81448dc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81450eee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81453609)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814562bd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81462b48)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8146ec85)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8147716d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814868d3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/key.c (ffffffff81495f8e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a0e70)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf32)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff815145bf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d715)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81540f28)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81554c21)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156c0bb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81578a8a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff8158e9e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff815e3f7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff815e579c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/nmi_backtrace.c (ffffffff815ed561)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81610451)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8161ccc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d2dd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff82d0f7af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff8169065b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710845)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c83e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dea5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff8174ac08)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
```
```
In drivers/tty/vt/vt.c (ffffffff8174eecf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81783b0c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8178dbd6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817affb2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81816063)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8181c550)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81826871)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ab2d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81832ee9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81835e65)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff81868b6d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff81880495)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8188d143)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818b7d80)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818bca01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818d2202)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190309c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191fedc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff8193c243)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941f12)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944d42)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195dc73)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81973e15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81992e77)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff819fffd6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_hash_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81a2291e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81a35fa3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81a3e485)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a64635)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a76296)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ethtool/ioctl.c (ffffffff81a83af6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81abb862)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2250)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8057)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e93)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01ccb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d945)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b693d7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b7525b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b81403)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/mptcp/protocol.c (ffffffff81bac65a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_ready
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
In arch/x86/events/amd/ibs.c (ffffffff8100a77b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810186af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028a98)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fc5c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff82fbb087)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8104100d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049519)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067bf4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106922f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a70c0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810aa5b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c1315)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff810c907f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81c41cdf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111e33b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff81121db9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112b5c7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81154088)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8115561c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/futex.c (ffffffff81157384)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff811956bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff811a192e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81be501b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff81230df6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8124ff7b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_take_insn_slot
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125d81b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__wait_on_page_locked_async
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812617ca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812656b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81266cc6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff8126aa2c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/truncate.c (ffffffff8126b37e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8127576e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page_prepare
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812798b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff812811ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff812921c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81296e5e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a215f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812a3cde)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff812b1cd5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c2c41)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812c3e16)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812c4d3c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812ca183)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812d6385)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e1ee8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812e60b6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812eee66)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f9635)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812fdf0e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81306239)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8130db0b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81312596)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff813138c2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff81315002)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/pipe.c (ffffffff81329dd7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff8133c816)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff8135bb22)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/splice.c (ffffffff8135d6be)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813669f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff8136b423)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io_uring.c (ffffffff81399a7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/mbcache.c (ffffffff813b5fb9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813bbad0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff813bf7c2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff813c349c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/balloc.c (ffffffff813ebbc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ef65c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff813fb0e3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff813feebc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81401b1c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81404cca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81412a35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141513f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8141c044)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8142104c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142a21c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff8142d546)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81446733)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81451972)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_update_super_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff8145428b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff8145b6c0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cb4e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff8145e565)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8145fb19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81465965)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d40e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8146fab9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147267d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e648)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8148941f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81491fad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814a3f83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/key.c (ffffffff814b39ee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814be820)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a142)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8153169f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a585)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8155dbb8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff8157138c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff81586deb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81595638)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff815ab542)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In lib/irq_poll.c (ffffffff816084af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff81609b75)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/nmi_backtrace.c (ffffffff81611d21)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff816366cd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a092)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff816433f3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d9fd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff82ffd230)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff816ae37b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d425)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff817589ae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81759e05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81766378)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
```
```
In drivers/tty/vt/vt.c (ffffffff8176a851)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8179b05c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff817b9946)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817c4b35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff818251f3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8182b5a0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837391)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b7ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81843aea)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81846985)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff8187797d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff8188ed45)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8189b3c6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818c6690)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818c9711)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818dc5e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190b965)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819275d8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81942233)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81948262)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ad82)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964663)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81975efd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81978d15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996097)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff81a00016)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81a22c7e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81a38373)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81a41235)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a6c775)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7f006)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ethtool/ioctl.c (ffffffff81a8d626)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7442)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc80)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3eb7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02d03)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0fdab)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebd9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c215)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77e07)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fcb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90c43)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/mptcp/protocol.c (ffffffff81bbecca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81bc2bdc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
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
In arch/x86/events/amd/ibs.c (ffffffff8100b04b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810199d2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a625)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103076c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff831c58ff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810429fd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bfeb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067fff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81069c25)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a8160)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810ab80b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c2cf5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff810caa7b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81c33c4f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111e64b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff81122139)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112b893)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff81137e7d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811554f9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81156bb3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81158798)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811a252e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81bd6e0b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff81234f99)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81256dde)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812605e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81264f91)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8126a1b3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8126b6f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff8126fc0c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/truncate.c (ffffffff81270473)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8127aa8e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8127ea0d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8128631d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff81297f0b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129caae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812a79ef)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812a946e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff812b73a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff812c9abd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812cac1a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff812cb9cc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d0c67)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff812dd52f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812e96a3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ed846)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812f4ff6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81300169)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813048bb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8130c70d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81313d1e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8131807b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81319a52)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff8131b742)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/pipe.c (ffffffff8132fd97)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81342c9b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81362732)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/splice.c (ffffffff8136415e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8136d2a6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff81371cc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io_uring.c (ffffffff81391e90)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In fs/io-wq.c (ffffffff813a1fc8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/mbcache.c (ffffffff813bd109)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff813c2bc0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff813c9a82)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/balloc.c (ffffffff813f2105)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f5b1b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814015b3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814051d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81408061)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8140b235)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81418e95)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141b03c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff814222bb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff814277fc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81430f1c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff81434206)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8144bee3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81458970)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81459bbb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff81461000)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff81463dea)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff814651f9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8146b115)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff81472a90)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81474f7a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147808d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81484118)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8148ecaf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8149716d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814a9eb7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/key.c (ffffffff814b981e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c4b4d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a51)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81539b2f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542c45)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81566418)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff815793bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff8157e1b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-cgroup.c (ffffffff8158dc2a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff8159c289)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff815b63a4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815eb10f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff815ecdc1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/nmi_backtrace.c (ffffffff815f5401)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81619d1d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dce2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff81626213)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816706ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff83208825)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff816908db)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710805)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c84e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dca5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749fc6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8177db9c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783b3b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff8179caf6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817a7997)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81808583)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8180e8c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a541)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ea0d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81826c9a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818297e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff8185a15d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff818714d7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8187e056)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818a9a7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818ad041)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818bf7c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ec9ae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190ac98)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81925a63)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bbc2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e8c2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948a83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff8195a0c7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff8195c205)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197ae67)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff819e6576)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81a09ffe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81a1f1b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81a25e95)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a54f05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a67ea6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ethtool/ioctl.c (ffffffff81a76196)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2465)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8ff0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abef79)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee607)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afd99d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c864)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e75)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66912)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c4d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7fe57)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/mptcp/protocol.c (ffffffff81bb08b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:__mptcp_flush_join_list
```
```
In net/mptcp/subflow.c (ffffffff81bb3078)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
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
In arch/x86/events/amd/ibs.c (ffffffff8100b55b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e6f2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ec35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103563c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff832a6677)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff81048d6d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810533ec)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107247f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81074335)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810b9c10)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810bd25b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810d5835)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff810ddbfb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81d5260f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8113eaf2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811426e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8114c383)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff8115abd0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8117988e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8117b946)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8117d6a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811cbd0e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81cb3f19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8126f0c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81292b6e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129cfd3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812a17c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812a6e46)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff812a83d6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/readahead.c:read_cache_pages_invalidate_page
```
```
In mm/swap.c (ffffffff812aced8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/truncate.c (ffffffff812ae109)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b8aee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff812bc58c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff812c562c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff812d894b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812dd87e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812e900f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812ef639)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/rmap.c (ffffffff812f99f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8130eadd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8130fc18)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff813109df)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swapfile.c (ffffffff8131633e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff813246d8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813315dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81335bbd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8133f5f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81349db9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8134e61f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8135790d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff8135effe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81364582)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
```
```
In mm/balloon_compaction.c (ffffffff81366242)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff81368a12)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/pipe.c (ffffffff8137d557)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff813906db)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff813b0f32)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/splice.c (ffffffff813b294e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff813bbf86)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff813c0ce3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io-wq.c (ffffffff813f1373)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_queue_worker_create
```
```
In fs/mbcache.c (ffffffff8140cea7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff81412d98)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff8141a338)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/balloc.c (ffffffff814440e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8144837b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81453b3c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814579e4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145a99d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8145deb4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8146c0c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8146df40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff814759f4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8147b44d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81487c69)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8149ff57)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff814aca83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff814adcab)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff814b184c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/transaction.c (ffffffff814b64e0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b76db)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff814b93bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff814bab79)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff814c17c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff814c955d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff814cd528)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf30d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff814db798)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff814e671e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff814eea5d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81502367)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/keys/key.c (ffffffff8151204e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d52c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebf1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8159849f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a3165)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff815ca7e8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff815de5fc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff815e38b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-cgroup.c (ffffffff815f369a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff816048bd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff8161c8d4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8165760f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/ubsan.c (ffffffff816599d5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
```
In lib/sbitmap.c (ffffffff81659ce1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/nmi_backtrace.c (ffffffff81662871)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81688ffd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d302)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff81695a53)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e49bd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff832f09c0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff8170634b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d1f4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff817be235)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff817cb621)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81803d8c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a55b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff818257c6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81892d53)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81898ea1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4a81)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a909d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff818b25e7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b5345)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff818e8c4d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff81901bb7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8190f840)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff8193e98f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff819420e1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff81955e34)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819890cd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab348)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff819c89d3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ced82)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1af2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819eda83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff819ff897)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81a01a15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81a05f3e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a2423a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/dev.c (ffffffff81a96aa6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81abc50e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81ad3447)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/netpoll.c (ffffffff81adabf5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81b0dc15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b218d6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ethtool/ioctl.c (ffffffff81b307d6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f2e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763f0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7caa5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa9d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa54)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde49a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e4aa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ioam6.c (ffffffff81c3a19d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d18d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b6f7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/mptcp/protocol.c (ffffffff81c7e8d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81c81728)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81c83d0b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
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
In arch/x86/events/amd/ibs.c (ffffffff8100bf8b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102121f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81033ea5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b46c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83455891)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810520ea)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ee8c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8108062f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81082b6d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810d0710)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810d439b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810eebc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff810f773c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81f22ab6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81162168)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff8116623c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff81171cfd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff81184497)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee2d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811b0fe9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff811b2724)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff811ffab9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81e64dc7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812be019)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e858d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f4060)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812f94c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812ff061)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8130762c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8131458e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813185e7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813312cf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813375f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff81342559)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff8134c06f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81352ab1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/rmap.c (ffffffff8135bfb7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff8137691c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b731)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swapfile.c (ffffffff81381496)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81392c5b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff813a2454)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff813a7374)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff813b5240)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b6f26)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c07c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c518a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff813d0668)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff813da0b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In mm/zsmalloc.c (ffffffff813e2887)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff813e3227)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff813e6551)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In fs/pipe.c (ffffffff813fe37a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81413192)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81435dc6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/splice.c (ffffffff814389fa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff81441e9f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff8144503b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/mbcache.c (ffffffff81481cf9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8148a879)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff81493328)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/balloc.c (ffffffff814bffdb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c48cc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814d101f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814d53dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d871e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc5b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814ec0bf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814eec97)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f7cd0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff814fd8ad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8150b546)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81526b8b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81534a3f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81535b9b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8153a3a3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8153cd3b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8153fdd4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540eba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff815430e8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81544a19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8154c15b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff815556f7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8155930f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be24)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81569336)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff815744ae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8157f18b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff815939b9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/keys/key.c (ffffffff815a44be)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b08dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6eb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8163cd3f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff816499a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81675d68)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff8168c751)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff81692b11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/partitions/core.c (ffffffff81e8c64c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-cgroup.c (ffffffff816a4caa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff816b804d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In io_uring/io-wq.c (ffffffff816da1a4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff816ea0e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176ef1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/ubsan.c (ffffffff81772005)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
```
In lib/sbitmap.c (ffffffff81772436)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In lib/nmi_backtrace.c (ffffffff8177c6b8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff817a63fd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abeba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff817b6813)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f3af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff834a894c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff818344ab)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c52f0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff818fa515)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81908e55)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff819436ac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a2c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff81965396)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff819dd007)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff819e2de9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eea65)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f2fe7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd6aa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01fae)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81a534e7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81a62e1b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81a969c7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81a99fb3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81aaf08d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae2ee1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b090f8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81b29953)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30b05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b340c3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b543a3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81b66e0a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81b69937)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81b6dc77)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8d93a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/dev.c (ffffffff81c0d98c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/link_watch.c (ffffffff81c37217)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81c50cf9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5baa5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81c94ff5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ca9f56)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81cbb673)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe96a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05bcc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c9a0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418ca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d55e07)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68145)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81d752b4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbcda)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb51c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deae1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e24066)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81e271b8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81e29ef0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
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
In arch/x86/events/amd/ibs.c (ffffffff8100efbb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025bff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b935)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043c3c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83e737c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8105f92a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d5fc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092fea)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8109562d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810eeff0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810f322b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff8110feb5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff81119ed9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/build_utility.c (ffffffff820cd406)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81195bd8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff8119a3ac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811a83bd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811bf741)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef5ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811f1c29)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff811f35c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff812474d9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff812481f1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff813216ab)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134d55e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8135222d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8135e351)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81363244)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff813697e6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff8137174a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813886ce)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8138c4db)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813a7f94)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813ae720)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813ba6a6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff813c4c2f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813c6b89)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff813d7527)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff813f4279)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff813f90b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813ffcda)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff814115f8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff814220b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff81429f9a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/migrate.c (ffffffff8143527b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143a43f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8144316b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814494f5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81455d56)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff8146184e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In mm/zsmalloc.c (ffffffff81469de7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8146aba3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff8146e01e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff8146f864)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff81487fea)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff8149e44c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff814bf945)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff814c6ffa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff814d097c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff814d33d1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/mbcache.c (ffffffff81514f62)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8151e126)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff81526fe8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/balloc.c (ffffffff81557fe6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155ce0c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81569a63)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff8156e33a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81571506)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574bbb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81585e29)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81588d5b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81592290)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8159808d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815a61e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff815c446b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff815d2f6c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/ext4/fast_commit.c (ffffffff815d404b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff815d8913)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff815db500)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff815de96a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815e000d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/jbd2/recovery.c (ffffffff815e1f40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff815e3b29)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff815ebf3b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6b2b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff815fc414)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdd1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cec6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81619d3e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81624e58)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8163c54e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/keys/key.c (ffffffff8164e581)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b2bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff816d11a0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff816f465f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702975)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81731d28)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/genhd.c (ffffffff81750f91)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/partitions/core.c (ffffffff81754518)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81763a50)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81778668)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff817a6234)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff817da308)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8189e94f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff818a20f9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
```
In lib/sbitmap.c (ffffffff818a2cba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff818bae8d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c47fa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff818d1063)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e14f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff83edf75d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff81968f48)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07876)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15bd0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a535b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a63445)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81aa613c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aad931)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff81ace7c6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81b5875d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81b5ea39)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c175)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70d57)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7babd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b8066e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81bdc8b6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81bee0cb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81c19577)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e513)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81c36b8d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6e981)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98dec)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81cbd573)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5425)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc90a3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced123)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81d02678)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81d05555)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d0a162)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d29e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/dev.c (ffffffff81dc10fc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/link_watch.c (ffffffff81dea617)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81e0639e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e11ed5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81e50ad5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e66fe6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81e79c03)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ec387c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecad1c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed23d1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f2053b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331d9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9cdeb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ioam6.c (ffffffff81fa98f7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae120)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbea03)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff8111)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81ffe928)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82002000)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff82039188)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100e59b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025b1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103ba15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043d50)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83695281)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8106107a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095f3a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81098550)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810fafa0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810ff56b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff8111c4b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff81127149)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (ffffffff8114301e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff82151886)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff811a7586)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811ac0d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811ba08d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811d2221)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81203d83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff812063d7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff81207d7a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff8125e599)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/offload.c (ffffffff8135124c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/cpumask.c (ffffffff8135d825)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137e4ff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8138343d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813910c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81395674)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8139b983)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813a385a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813ba85e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813bf848)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff813db573)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3020)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff813ef066)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff813f919f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813fb016)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff8140ba34)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff81427b3f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8142be81)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81432b7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff81444ac3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81456d9a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8145f439)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/migrate.c (ffffffff8146a7e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146fd8f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81478107)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8147f6e6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81488f0f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff8149706d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/zsmalloc.c (ffffffff8149efe7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff8149fa33)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/page_idle.c (ffffffff814a2894)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814a4044)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814bcee2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff814d376c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff814f4a45)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff814fc438)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8150707c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/buffer.c (ffffffff8150a661)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/mbcache.c (ffffffff8154c962)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8155628c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff8155f4bb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/balloc.c (ffffffff8158fd33)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81594c2c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815a1853)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815a61fa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a926d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815aca8b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815bc6ff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bf5d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c9367)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff815ceb3d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff815dca59)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff815fbb4c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8160aaba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc2b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff816104b4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff81612fb0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff816163ca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617329)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8161975c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a7c0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff8161b2e9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81623a1b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ebe6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff816343a4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635cd0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff81644d76)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81651eee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8165d1de)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff81674a07)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/keys/key.c (ffffffff81686de1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81693bb9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8172e77f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173c9a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8176e0a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81787604)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff8178d561)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_mark_disk_dead
```
```
In block/partitions/core.c (ffffffff81790638)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a2afd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff817b81a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff817e7194)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In lib/rhashtable.c (ffffffff81819689)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff818e0f1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff818e4529)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
```
In lib/sbitmap.c (ffffffff818e5ca1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff818fdf8d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819078ca)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff81914053)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198264f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff837051ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff819af538)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50706)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec10)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a9da05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aadb05)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81af193c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af91c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b01e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/iommu/iommu.c (ffffffff81b1d166)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81babccd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81bb1fe9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf955)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc4587)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf7e0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd46ee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81c33c76)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81c465fb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81c80597)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c853fb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81c9de7d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd5f94)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00187)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81d24e83)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d0b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30dc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55e63)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81d6b5b9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e635)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d7329b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9650e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81dd5d64)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
```
In net/core/dev.c (ffffffff81e30d4c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/link_watch.c (ffffffff81e5bdf7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81e78c21)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e857e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81eac2e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec2da6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f03)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81f21abc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29850)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f310c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a219)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f80037)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92559)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd8af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ioam6.c (ffffffff8200a277)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e8cb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f8d9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82074641)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff82079da9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff8207dc10)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/handshake/request.c (ffffffff82093834)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/nmi_backtrace.c (ffffffff820b7498)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff81013d9b)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102bc7f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81041ed5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a250)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff838c51c1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8106814a)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d47a)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8109faf0)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff81104440)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In kernel/softirq.c (ffffffff81108c1b)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff81126c25)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (ffffffff81131729)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (ffffffff8114e4ee)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff822346c6)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff811b70e6)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811bbcd0)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811c9f4d)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811e6ea1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a343)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8121d5e7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff8121ef0f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/watchdog.c (ffffffff812784d9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/offload.c (ffffffff813786ac)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In kernel/bpf/cpumask.c (ffffffff813865c5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a775f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac857)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813bae64)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff813bf434)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff813c43f5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:folio_mark_dirty
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/truncate.c (ffffffff813cd3bf)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813e397e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff813ea861)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/compaction.c (ffffffff81404e32)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140d857)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_pages_dirty_lock
```
```
In mm/memory.c (ffffffff8141af6e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff81424d4f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81426c66)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In mm/rmap.c (ffffffff814382f4)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:folio_referenced
```
```
In mm/slub.c (ffffffff8145a682)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff8146134f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff814655db)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146bf9e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/hugetlb.c (ffffffff8147eb1a)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8149189e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff814997c9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:writeout
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149f00c)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a784e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814adbba)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff814b8f75)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff814c6402)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
```
```
In mm/zsmalloc.c (ffffffff814ce747)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffff814cf183)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/userfaultfd.c (ffffffff814d2c64)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/page_idle.c (ffffffff814d3731)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814d4ef4)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
```
```
In fs/pipe.c (ffffffff814ef37f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_try_steal
```
```
In fs/dcache.c (ffffffff81505eec)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81529155)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff815301f9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
```
```
In fs/remap_range.c (ffffffff8153c3a2)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In fs/buffer.c (ffffffff8153f611)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/mbcache.c (ffffffff81582792)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8158c75c)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff81595bab)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/balloc.c (ffffffff815c88c2)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cd8dc)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815da603)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815df079)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e7c)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e582a)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815f54dc)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f8376)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81602147)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff816073bd)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff8161533f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff816346ec)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8164386a)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff816449eb)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff81649274)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8164bdb0)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8164f1ec)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650143)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81652681)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff816536e7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/revoke.c (ffffffff81654209)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8165cabb)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff816680ad)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff8166d883)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f1bf)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e296)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8168b4fe)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81696f3e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff816b0dc7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In security/keys/key.c (ffffffff816c32f1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d01b9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/apparmor/policy_unpack.c (ffffffff81747bb0)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8176f0df)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177d7a5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/bio.c (ffffffff817abb00)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In block/blk-core.c (ffffffff817b02d8)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff817c9ce1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff817cfdc1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:__blk_mark_disk_dead
```
```
In block/partitions/core.c (ffffffff817d3ed8)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e663d)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff817fca68)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff8182cf54)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
  - io_uring/io-wq.c:io_queue_worker_create
```
```
In io_uring/futex.c (ffffffff8182f0d6)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wakev_fn
```
```
In lib/rhashtable.c (ffffffff8185e9d9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81927a8f)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff8192b529)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
```
In lib/sbitmap.c (ffffffff8192cca1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
```
In drivers/gpio/gpiolib.c (ffffffff819455fd)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950d52)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff8195bf93)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9dcf)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff8393871d)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff819f99e8)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c3d6)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1347)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81af04f5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b00735)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81b44e9c)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c7e4)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70b4e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/iommu/iommu.c (ffffffff81b736e6)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81c0000d)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81c064d9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c140d5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c191a7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81c24440)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2935e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81ce8e66)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81cfbf0b)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81d34f67)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81d39dfb)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81d52a2d)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8af74)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5c20)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81ddabf3)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2f95)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6d93)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0cd73)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81e215de)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81e263fc)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81e2a3de)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e16e)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81e8df26)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
```
In net/core/dev.c (ffffffff81eef2e5)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_device_attach
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/link_watch.c (ffffffff81f1b1b7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/xdp.c (ffffffff81f38af1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47715)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81f6ed75)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f86188)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81f99a63)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5a4c)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee3c9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7039)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff820081f3)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/inet_fragment.c (ffffffff820308c9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff820466b7)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff820602c9)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc754)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ioam6.c (ffffffff820d9218)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd85b)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eea09)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff821489e1)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff8214f209)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/handshake/request.c (ffffffff8216a0e4)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/nmi_backtrace.c (ffffffff82191648)
Location: arch/x86/include/asm/bitops.h:135
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a58b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810256a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cffb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032bdf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103e15d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810473d3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106136e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8109de90)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810a0ff5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b9425)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c08a6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a6f3df)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110ed2a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff8111b671)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81140778)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81141e7c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81142d13)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8117c87c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff811882e4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81188db2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811fa472)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff81214e55)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c3f4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff81221363)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81224c43)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81227e96)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff8122b185)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff8122bea9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81234b15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123996b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8124122d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff81252610)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255ac4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125f588)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81260bee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff8126da11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff8127ad57)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a6bfdd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127ce96)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127ea07)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127f47d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81283caa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128f73d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81299aa0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812a0698)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a8559)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b1a40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812b4ba5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812bca50)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c41e8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812c8335)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812ca241)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812cbcbe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff812d3ca9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812df67c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812f0706)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81307b25)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff8130eade)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8131b3a3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81357c5d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8135bc4f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff8135ebc1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff81360059)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff81386d40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138d6e4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81398fc2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8139b7c9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139ec86)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813ad381)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9e64)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813c3a51)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c5cc1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813d9481)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e4241)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ea8bb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb2f7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed49e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813eea89)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f3bd0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb84b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813fdc19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400f19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cdf8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81418525)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8141f1b9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8142f3a9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff8143d2fb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81447ca1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b22b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814ad5ff)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5935)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-core.c (ffffffff814da848)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814ecb81)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8150373b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81510ce8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff81523a36)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81552c1f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8155420c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8155fb61)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8156ce31)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b726e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828e1c10)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815d7be8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816266b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8165030e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81651895)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165e2f8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81661761)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8169469c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8169f896)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816bc553)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff8170b163)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81711340)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171ab9e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d33d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81724ce9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817270b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/nvme/host/core.c (ffffffff81744aad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/ata/libata-scsi.c (ffffffff81760fdd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81787138)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817a0c15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817a55c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817b9cb2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e7322)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/rtc/dev.c (ffffffff8181b303)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834e43)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81848885)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81865817)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818cc903)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff818f1ae7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff81902c7c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e94)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/netpoll.c (ffffffff8190aa62)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8192cc35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81940581)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff8196f47f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81975be4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ad6d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819b2127)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c9d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff819cab06)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0fef9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a391)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a51b11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff81008c8b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016be5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/idt.c (ffffffff8102251f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8102d971)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036557)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810517ce)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8108c8b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff8108fa15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810a7d65)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810af0a6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a2b80f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810ffa6f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff8110c6e1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff811334f8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811351dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81136073)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8116fa5c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff8117b424)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8117bef2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811ed1c2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff81207bc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f5de)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff81214513)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81217df3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff8121afd6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff8121e295)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff8121ef89)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81227b85)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122c99b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8123422d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff81245b2e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812481a4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812519a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125300e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff8125fa41)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff8126cc37)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a28524)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8126ed4a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff81270837)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127129d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81275b33)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281406)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff8128b660)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812921a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81299f19)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a2e10)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812a5bf7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812adbb0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812b5228)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812b9375)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812bb281)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812bcb2e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff812c4929)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812d02bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812e1336)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff812f8745)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff812ff6ee)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8130bf43)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8134890d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8134c8ef)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff8134f861)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff81350cf9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff813777d0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137e174)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389a52)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138c259)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138f716)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8139de11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aa8f4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813b44d6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813b6741)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813c9f01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d4cc1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813db33b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dbd77)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ddf1e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813df509)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813e4650)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec2cb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813ee699)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f1999)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd878)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81408fa5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8140fc39)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8141fe29)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff8142dd6b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff814386f1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc4b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149e01f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a6355)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-core.c (ffffffff814cb1f8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814dd0d1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814f3bfb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81501008)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff81513d16)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81542f2f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8154448c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff815509b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a604e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/ec.c (ffffffff815c17a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/acpi/nfit/core.c (ffffffff815f915e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_ars_rescan
  - drivers/acpi/nfit/core.c:scrub_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ad35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8163075e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81631cd5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163e678)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81641ae1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8167208c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8167d286)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816debe3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816e4dc0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f3ffe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f679d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe119)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817004e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/nvme/host/core.c (ffffffff8172673d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/ata/libata-scsi.c (ffffffff81740e3d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81766a88)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81792a55)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81797081)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817ab6e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca98c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff817e29f3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc4d3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff8180fee5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182e4c7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184eb60)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_isr
```
```
In drivers/hv/connection.c (ffffffff81850026)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_on_event
```
```
In net/core/dev.c (ffffffff81886993)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff818ab927)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff818bcaac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcc4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/netpoll.c (ffffffff818c4652)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818e6735)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818fa071)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81928f4f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f6a4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193482d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe90)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff8196e757)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da8d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff819878f6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cccb9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff819d7151)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26b6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81a0ec11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100a54b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017775)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025505)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce5b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032a3f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103df9d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047213)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106179e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8109de40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810a0fa5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b8985)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810bfdf6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81adb7ef)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110cc1a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81119561)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e628)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113fd2c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81140bc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8117a64c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff811860b4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81186b82)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811f8242)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff81212bf5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a194)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff8121f103)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812229e3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81225c36)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff81228f25)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81229c49)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812328b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123770b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8123efcd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff812503b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253864)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8125d328)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125e98e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff8126b7b1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff81278af7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81ad83ed)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8127ac36)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8127c7a7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8127d21d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81281aba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d54d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812978b0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8129e4a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812a6369)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812af850)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812b29b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812ba860)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c1ff8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812c6145)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812c8051)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812c9ace)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff812d1ab9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812dd48c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812ee516)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81305915)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff8130c8ce)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81318e73)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff8135572d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8135971f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff8135c691)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff8135db29)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff81384810)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138b044)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81396822)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81399029)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139c4e6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813aabe1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b76c4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813c0ee1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813c3151)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813d6911)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e15c1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813e7c3b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8677)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea81e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813ebe09)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813f0f50)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8bcb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff813faf99)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe299)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a178)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff814146c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff8141b359)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff8142b549)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff8143949b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81443d41)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814972cb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814a969f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b19c5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-core.c (ffffffff814d68d8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814e8c11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814ff7cb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff8150cd78)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff8151fac6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8154e95f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8154ff4c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e6d1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8156bd71)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b77fe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828f4aa0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815d9fd8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654685)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167e6ce)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8167fc55)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168c6d8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff8168fb41)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816c290c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816cdb06)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816eaa23)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81749f33)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81750110)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175996e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c10d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81763ab9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765e85)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81790d6d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817b74e8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817dd6b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817e2061)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817f6752)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81823dc2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff818422bc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff8185c7e3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81861f94)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864e92)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884473)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81897eb5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b65a7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8191d903)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81942b17)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff81953cac)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954ec4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/netpoll.c (ffffffff8195ba92)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8197ddc5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81991711)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199fc7a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a72bf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819abbb9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
```
```
In net/ipv4/tcp_output.c (ffffffff819d9c4f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819e03b4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e553d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c70)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9c7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b71d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35586)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a979)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81a84e11)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a90376)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81abdf01)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100a6ab)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810179b5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f65)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dc4b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff8103399f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103f0e0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048613)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81062d4e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a5d30)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/softirq.c (ffffffff810a8f25)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c1105)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c82d6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81ae7d8f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111817c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81124c71)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b136)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114c85c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8114de1e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8118805c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/watchdog.c (ffffffff81193a04)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811944d2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812065a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/uprobes.c (ffffffff81221b72)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122926b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff8122e153)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81231bc3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
  - mm/page-writeback.c:write_cache_pages
```
```
In mm/readahead.c (ffffffff81234f36)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/swap.c (ffffffff812382e5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81239044)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81241d75)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246c45)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8124e71d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/gup.c (ffffffff8125fd34)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126322d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff8126cd0e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8126e35e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In mm/rmap.c (ffffffff8127b141)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffff812886e7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81ae48a8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/madvise.c (ffffffff8128a817)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8128c377)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8128cddd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812917c6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129d2fb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812a7687)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812ae222)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff812b6684)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812bfb90)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812c2bf2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812cafa0)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812d2a93)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812d78dc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/balloon_compaction.c (ffffffff812d8d61)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In mm/page_idle.c (ffffffff812da7be)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In fs/read_write.c (ffffffff812e28d2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/pipe.c (ffffffff812ee404)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff813004dd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff81316c85)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff8131e0f5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8132aaa3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mbcache.c (ffffffff81368d28)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136ce1a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/iomap/seek.c (ffffffff8136fdbe)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/iomap/seek.c:page_cache_seek_hole_data
```
```
In fs/quota/dquot.c (ffffffff813713b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff8139838b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139ed7f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aaaa8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae202)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b09fd)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813bf52c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc3cf)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff813d6018)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813d82fc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff813ebbba)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813f69d2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813fd442)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fdea1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81400180)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff814017a9)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81406b17)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ea15)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/dir.c (ffffffff81410bc8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f40)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fe71)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8142af35)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/file.c (ffffffff81432384)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In ipc/util.c (ffffffff814424e2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/key.c (ffffffff8145068b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff8145b071)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814af3aa)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814c202f)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca445)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In block/blk-core.c (ffffffff814ef4e8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81501bb1)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8151899b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81526458)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/rhashtable.c (ffffffff815393b2)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff815687af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff81569d8c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff81578561)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81586271)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d1269)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828f9ef8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815f3e98)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ede5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff81698d2e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8169a2a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a6cd8)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff816aa141)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816dcedc)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816e8046)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81705263)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff817653b3)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8176b590)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81774e8e)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff817777ad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f119)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781515)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff817aabad)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817cf58b)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817f7985)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817fc497)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff81810992)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183f842)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c6ec)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff81877a63)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d1f4)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880142)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189ff33)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff818b40a5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d2857)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8193ee13)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff81964647)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/xdp.c (ffffffff81975436)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976ea6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/netpoll.c (ffffffff8197de82)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff819a06f5)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b419d)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff819e38af)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea072)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef1eb)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b554)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff81a2798a)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d6c)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40ee6)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a871b7)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6mr.c (ffffffff81a91794)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf77)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In lib/nmi_backtrace.c (ffffffff81aca388)
Location: arch/x86/include/asm/bitops.h:136
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
