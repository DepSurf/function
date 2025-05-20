# Function: <code>test_and_set_bit</code>

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
In init/do_mounts.c (ffffffff81002715)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100908c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015d8c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu.c (ffffffff810202a5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102b758)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/process.c (ffffffff81039252)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041092)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8104ef7a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81050fa4)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
```
In arch/x86/kernel/hpet.c (ffffffff810623ac)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In arch/x86/mm/pgtable.c (ffffffff810710b5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_splitting_flush
```
```
In kernel/softirq.c (ffffffff81084d41)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In kernel/sys.c (ffffffff81092b6b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/workqueue.c (ffffffff8109865b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
```
In kernel/pid.c (ffffffff8109e1f9)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (ffffffff8109e83a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (ffffffff810a019d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/sched/fair.c (ffffffff810be731)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/wait.c (ffffffff818209bf)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810da82f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd691)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff810fedc5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/futex.c (ffffffff810ffab7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8112f98c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In kernel/watchdog.c (ffffffff8113aa9b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (ffffffff8118776f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff8118daa6)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81190a3a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/page-writeback.c (ffffffff81198af1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/readahead.c (ffffffff8119bc16)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/swap.c (ffffffff8119d390)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff8119e900)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811a0b41)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:zone_reclaim
```
```
In mm/shmem.c (ffffffff811a916c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/vmstat.c (ffffffff811ad4eb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/backing-dev.c (ffffffff811ae9e0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/gup.c (ffffffff811ba5f8)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bbdfd)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (ffffffff811c2f01)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mmap.c (ffffffff811c8369)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/rmap.c (ffffffff811cc305)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/swap_state.c (ffffffff811d29a7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811d4773)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811dedad)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e4b66)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff811e9b7d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In mm/migrate.c (ffffffff811f0eee)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f522e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff811fbd7e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81201d02)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
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
In mm/zsmalloc.c (ffffffff8120545c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
```
In mm/balloon_compaction.c (ffffffff81207385)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_putback
```
```
In mm/page_idle.c (ffffffff81208336)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/pipe.c (ffffffff81214ab1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff81223480)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/splice.c (ffffffff8123e7a9)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff81242965)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
```
```
In fs/dax.c (ffffffff8125dcc7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/mbcache.c (ffffffff8126cbdc)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/quota/dquot.c (ffffffff812706e9)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
```
```
In fs/ext4/balloc.c (ffffffff8128fcd3)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff81292488)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff81293520)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81296403)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/page-io.c (ffffffff8129f71f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812b8ca5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/resize.c (ffffffff812bef77)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff812c528e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d7954)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff812d923d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd0e9)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dfe6f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/crypto.c (ffffffff812e5490)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
```
```
In fs/jbd2/transaction.c (ffffffff812e8128)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
```
```
In fs/jbd2/commit.c (ffffffff812e9bde)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec25b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812eda27)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff812f1939)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
```
In fs/ramfs/inode.c (ffffffff81f97249)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff812f39a0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8130449d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8130fa85)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81316215)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff8132f50b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81336b68)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff81396a9f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In crypto/chainiv.c (ffffffff813a213f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - crypto/chainiv.c:async_chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_givencrypt
```
```
In block/blk-tag.c (ffffffff813bbece)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff813c1f55)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff813c21cb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_rq_timed_out_timer
```
```
In block/blk-iopoll.c (ffffffff813c2488)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-iopoll.c:blk_iopoll_disable
```
```
In block/blk-mq.c (ffffffff813c4205)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
```
In block/blk-mq-tag.c (ffffffff813c70b1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In lib/nmi_backtrace.c (ffffffff813edb77)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81424073)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
```
```
In drivers/pwm/core.c (ffffffff8142c4f2)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_enable
```
```
In drivers/pwm/sysfs.c (ffffffff8142d754)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473589)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
```
```
In drivers/acpi/ec.c (ffffffff814837aa)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_start
```
```
In drivers/tty/tty_ioctl.c (ffffffff814e83ee)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff814e9a12)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f2420)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
```
```
In drivers/tty/vt/vt.c (ffffffff814f83e0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81524ce5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8152ae39)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/base/node.c (ffffffff81560b5d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff8159adf7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8159fa0f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/fence.c (ffffffff815a3cc5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_signal_locked
  - drivers/dma-buf/fence.c:fence_add_callback
```
```
In drivers/scsi/scsi_logging.c (ffffffff815b7c8b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff815d48dd)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff815edadc)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/virtio_net.c (ffffffff815f0e0d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
```
In drivers/net/xen-netfront.c (ffffffff815fbe88)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/usb/core/hub.c (ffffffff81607f19)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff8160cf9a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff8161ed5f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81645510)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/rtc/interface.c (ffffffff81673c50)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff81675387)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8168b116)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/bitmap.c (ffffffff8169d405)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b20e4)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
```
In net/core/dev.c (ffffffff81715e7d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff8173069a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/flow.c (ffffffff81734408)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/core/netpoll.c (ffffffff81738f86)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff817412b5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81749d86)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81774a38)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81779ec2)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177df9b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817ad049)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_write
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f141a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In init/do_mounts.c (ffffffff81002775)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009358)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810154a8)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu.c (ffffffff81020295)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102aa68)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/process.c (ffffffff8103826e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040fac)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8104f150)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051157)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
```
In arch/x86/kernel/hpet.c (ffffffff81062230)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff81088615)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/sys.c (ffffffff81095cef)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/workqueue.c (ffffffff8109c09b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/pid.c (ffffffff810a18a8)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (ffffffff810a1f7a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (ffffffff810a38a3)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/sched/fair.c (ffffffff810c1f12)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/wait.c (ffffffff8189adc7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810dff65)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811049fb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8110635e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8110771a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff81137c7d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In kernel/watchdog.c (ffffffff81142fcb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (ffffffff8119b7a2)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a142b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
```
```
In mm/oom_kill.c (ffffffff811a50ad)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff811adca3)
Location: arch/x86/include/asm/bitops.h:204
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
In mm/readahead.c (ffffffff811b0d75)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/swap.c (ffffffff811b3870)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff811b43c3)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811bbfc1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811c0adb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffff811c7d90)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/gup.c (ffffffff811d5197)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d7037)
Location: arch/x86/include/asm/bitops.h:204
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
In mm/mlock.c (ffffffff811df06e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff811e0360)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In mm/rmap.c (ffffffff811e928c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811eecd7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff811f019e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff811f07a1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811f3ad3)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff811fd22d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff811fefb1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81205069)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8120c701)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81211d97)
Location: arch/x86/include/asm/bitops.h:204
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812180c7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121ad1d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81220d80)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81227d9e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122be72)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8122cef0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8122dcca)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/pipe.c (ffffffff8123b858)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8124bb63)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81266ec7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8126dbab)
Location: arch/x86/include/asm/bitops.h:204
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
In fs/dax.c (ffffffff81287ac3)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/crypto/crypto.c (ffffffff81288d31)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff81298a78)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff8129c18c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff8129d62e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
```
```
In fs/ext4/balloc.c (ffffffff812bd203)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812bfa56)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812c0ae1)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812cd94a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812ce016)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812e7afd)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812ee882)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff812f4b01)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813076b6)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff81308ff6)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d4dc)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8130fb20)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff81317238)
Location: arch/x86/include/asm/bitops.h:204
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
In fs/jbd2/commit.c (ffffffff81317af8)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319d6d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8131b369)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff81320a8f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff81fc1e10)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d64)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8133856c)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff813435e5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8134a164)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff8136420b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff8136c0c0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff813d3007)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813d84ca)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In block/blk-tag.c (ffffffff813ffcd7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff81405ee5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8140617f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff81407925)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
```
In block/blk-mq-tag.c (ffffffff8140b741)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In lib/nmi_backtrace.c (ffffffff81433d97)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In lib/irq_poll.c (ffffffff8146202f)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff8146d6fa)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
```
```
In drivers/pwm/sysfs.c (ffffffff81478ac7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1e4d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff81fcc8c0)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff814d2523)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/tty/tty_ioctl.c (ffffffff8153953e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8153acb2)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81546277)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81548a85)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81577c6e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8157e258)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/base/node.c (ffffffff815b52a4)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff815f0de9)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff815f5a4d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/fence.c (ffffffff815faef5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/dma-buf/fence.c:fence_add_callback
  - drivers/dma-buf/fence.c:fence_signal_locked
```
```
In drivers/scsi/scsi_logging.c (ffffffff81610533)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff8162e35d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff8164cc3e)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/virtio_net.c (ffffffff8165082a)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:skb_recv_done
```
```
In drivers/net/xen-netfront.c (ffffffff8165d293)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In drivers/usb/core/hub.c (ffffffff81668ce7)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8166cb46)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff8167f5bb)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a5f93)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/rtc/interface.c (ffffffff816d444b)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff816d5c37)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec9ea)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/bitmap.c (ffffffff816fe6d5)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81714259)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
```
In net/core/dev.c (ffffffff8177dd80)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff8179ae57)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/flow.c (ffffffff817a04d8)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/core/netpoll.c (ffffffff817a523d)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff817ae165)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b6cf6)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff817e1a08)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff817e7b58)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb3ea)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81861152)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ncsi/ncsi-rsp.c (ffffffff8188d735)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff8188e8b6)
Location: arch/x86/include/asm/bitops.h:204
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
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
In init/do_mounts.c (ffffffff81002795)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009398)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810157f8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu.c (ffffffff81020955)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In arch/x86/xen/smp.c (ffffffff8102ac04)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/process.c (ffffffff81037d3e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040a03)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81051950)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053a88)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
```
In arch/x86/kernel/hpet.c (ffffffff810652a0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff8108d645)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/workqueue.c (ffffffff810a10fb)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/pid.c (ffffffff810a6968)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (ffffffff810a7036)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (ffffffff810a8945)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/sched/fair.c (ffffffff810c7f20)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/wait.c (ffffffff818cf267)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810e68c2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c14a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8110dada)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8110eeda)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff81141a0d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114ccbe)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8114d638)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811ab18d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b1148)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff811b4def)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff811be2f1)
Location: arch/x86/include/asm/bitops.h:217
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
In mm/readahead.c (ffffffff811c1375)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/swap.c (ffffffff811c3f00)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff811c4a63)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811cc691)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d10c2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffff811d7eb0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/gup.c (ffffffff811e51b2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e9720)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811eee87)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff811f02ad)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/rmap.c (ffffffff811fa5dc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff811ff607)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81200b62)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120118e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81204606)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/hugetlb.c (ffffffff8120dcfc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/mempolicy.c (ffffffff812107f6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81217025)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8121e761)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81224001)
Location: arch/x86/include/asm/bitops.h:217
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a667)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122e664)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812334d0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8123a33a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123e3b5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8123f410)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124021a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/read_write.c (ffffffff812445e2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/pipe.c (ffffffff8124e5f8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8125eb43)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81278da4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff81280dfb)
Location: arch/x86/include/asm/bitops.h:217
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
In fs/dax.c (ffffffff8129bfde)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/crypto/crypto.c (ffffffff8129d9ff)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/mbcache.c (ffffffff812ad4f6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812b1cbc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff812b2f6e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
```
```
In fs/ext4/balloc.c (ffffffff812d2853)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/file.c (ffffffff812d4c66)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812d6111)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812e371a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/page-io.c (ffffffff812e3e06)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812fd83d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff81304852)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/extents.c (ffffffff8130aab1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d6a6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8131f006)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff813233d1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff81325940)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff8132d228)
Location: arch/x86/include/asm/bitops.h:217
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
In fs/jbd2/commit.c (ffffffff8132dae8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fd5d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81331359)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8133693f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff81ffe82a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8133dab2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e32c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81359bf5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff8135faa4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff8137aa2b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff813828e0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff813e9f4f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813f017a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In block/blk-tag.c (ffffffff81419584)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff81420175)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8142040f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff81422555)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
```
In block/blk-mq-tag.c (ffffffff81425e01)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In lib/nmi_backtrace.c (ffffffff81450031)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/irq_poll.c (ffffffff81480bdf)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff81482204)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8148f5ca)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
```
```
In drivers/pwm/sysfs.c (ffffffff81499e57)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3e3d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff820098c4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff814f49ff)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/tty/tty_ioctl.c (ffffffff81565c4e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81567372)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff815728c7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff815754e5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff815a414e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff815aa7f8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/base/node.c (ffffffff815e4570)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff8161e1ab)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8162370d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816292fc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b565)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_logging.c (ffffffff8163fdc3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/scsi/sd_zbc.c (ffffffff816488bc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd
```
```
In drivers/ata/libata-scsi.c (ffffffff8165f4ad)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff8167e970)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81696a07)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8169a846)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff816ad2f8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d4093)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/rtc/interface.c (ffffffff8170412b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff81705917)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171da8a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/bitmap.c (ffffffff81730335)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745f8a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
```
In net/core/dev.c (ffffffff817ab880)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff817c8bf7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/flow.c (ffffffff817ceea8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/core/netpoll.c (ffffffff817d3cab)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff817dd7f5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e6776)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81811f20)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81818318)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bd73)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8189308d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818c18e5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c2ba6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
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
In init/do_mounts.c (ffffffff81002325)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009078)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013cf8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020be5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810294c4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/process.c (ffffffff8103647c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e986)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8105142b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810533ea)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
```
In arch/x86/kernel/hpet.c (ffffffff810641e7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff8108a5b5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/workqueue.c (ffffffff8109e62b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/pid.c (ffffffff810a38d4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/task_work.c (ffffffff810a3f86)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (ffffffff810a576f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/sched/fair.c (ffffffff810c1bc9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/wait_bit.c (ffffffff819069ce)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810e5f13)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e4dd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8110f9da)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8111020b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8114324d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114ec3e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8114f64b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811b2706)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8598)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff811bc0d9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff811c7602)
Location: arch/x86/include/asm/bitops.h:217
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
In mm/readahead.c (ffffffff811c9665)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/swap.c (ffffffff811cc2f0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff811ccd3f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d52b8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d9afd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffff811e0a90)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/gup.c (ffffffff811ef07c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f486d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff811f9e54)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff811fb12d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In mm/rmap.c (ffffffff812052c9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8120a2cd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8120b837)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8120bfdd)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8120fa46)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81219b31)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (ffffffff8121c114)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81222aed)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8122a2ca)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8122f92f)
Location: arch/x86/include/asm/bitops.h:217
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812362a2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81238dac)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8123edb0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81245cd2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/zsmalloc.c (ffffffff81249df4)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8124ad63)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8124c0ba)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/read_write.c (ffffffff81250033)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/pipe.c (ffffffff8125a5b8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8126c513)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/splice.c (ffffffff81286314)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff8129038c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
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
In fs/crypto/crypto.c (ffffffff812ac6b5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/mbcache.c (ffffffff812ba99e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812befec)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff812c05b8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_idq
  - fs/quota/dquot.c:check_idq
```
```
In fs/ext4/balloc.c (ffffffff812e3ecf)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e9145)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/file.c (ffffffff812f1577)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/ext4/ialloc.c (ffffffff812f4491)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7c7f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812f9988)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8130795e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81314374)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff8131d9f2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff8131f3e6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81332593)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8133c829)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813423f8)
Location: arch/x86/include/asm/bitops.h:217
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
In fs/jbd2/commit.c (ffffffff81342c76)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344d0b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813462b9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8134b5ef)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff820e1a8f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813527ac)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81362eac)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff8136e3c5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81374697)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff8138e62d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81396f64)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff813f630f)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813fc32a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-tag.c (ffffffff8142747d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff8142e135)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8142e3cc)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff81431954)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_complete_request
```
```
In block/blk-mq-tag.c (ffffffff814339b1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff8143576c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81489dcf)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8148b42b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8149a20a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
```
```
In drivers/pwm/sysfs.c (ffffffff814a3aa0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814efbee)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff820eaf53)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815038d8)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/tty/tty_ioctl.c (ffffffff8157921e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8157a735)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8158697a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81589399)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff815b812c)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff815c03f6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff815d86d6)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/base/node.c (ffffffff815f9165)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff8163270b)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81638441)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163eed2)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff816410e9)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_logging.c (ffffffff81654803)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d1d7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
```
```
In drivers/ata/libata-scsi.c (ffffffff81673e7d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81693b65)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff816abd7d)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff816afa7e)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff816c24b3)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e87ca)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/rtc/interface.c (ffffffff81719bc0)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8171b5c7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8173593a)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff8173ad87)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff817481a5)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81761777)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff817ca089)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff817e77b7)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/flow.c (ffffffff817ee228)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/core/netpoll.c (ffffffff817f3023)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff817fce25)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81806536)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81832ada)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff81838818)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c431)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b9652)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ncsi/ncsi-rsp.c (ffffffff818e8265)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
```
```
In net/ncsi/ncsi-manage.c (ffffffff818e9545)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
```
```
In lib/nmi_backtrace.c (ffffffff818efdd1)
Location: arch/x86/include/asm/bitops.h:217
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In init/do_mounts.c (ffffffff81002359)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100968c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101464b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021788)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810296e4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/idt.c (ffffffff8102e0d3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103880c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041653)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8105510b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/hpet.c (ffffffff81068367)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff81091149)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
```
```
In kernel/workqueue.c (ffffffff810a4e8b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810aa5ac)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/kthread.c (ffffffff810abe7a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/sched/fair.c (ffffffff810c932b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/wait_bit.c (ffffffff81990a3e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810ee191)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff810f96cb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8111975d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8111acc0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8111b964)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8114ff01)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/watchdog.c (ffffffff8115b494)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8115bd64)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811c631d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ccd03)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff811d0d10)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff811dc430)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/readahead.c (ffffffff811de485)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/swap.c (ffffffff811e12e0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff811e1fd3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811ea7e8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811ef7ef)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff811f6a80)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/gup.c (ffffffff81206973)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120c647)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff812122a4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81213651)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/rmap.c (ffffffff8121e279)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff81223533)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81224d5d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8122560d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8122b2fe)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81234b7a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/ksm.c (ffffffff8123df54)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8124547a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8124c1c2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812550e2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8125977a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8125e930)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81265cf6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In mm/zsmalloc.c (ffffffff8126a028)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8126afd3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff8126c49a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/hmm.c (ffffffff8126d063)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81271f28)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/pipe.c (ffffffff8127c8b8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff8128e6a3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff812a33bb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/splice.c (ffffffff812a8d94)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812b30e1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
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
In fs/crypto/crypto.c (ffffffff812cfed5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff812de27e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812e2a5f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff812e3e5e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff813088bf)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130dbe5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318bd1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c2bf)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8131dfc8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8132c5ae)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338b34)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff81342002)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81343a86)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81356aa3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81360dac)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81366a28)
Location: arch/x86/include/asm/bitops.h:218
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
In fs/jbd2/commit.c (ffffffff813672a9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff813693ab)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8136a949)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8136fc1f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff826ea716)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813772c1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff81387b4c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff81392fde)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff81399367)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff813b3acb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff813bc744)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8141e40f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814247fa)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-tag.c (ffffffff8145247d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff81459369)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff814595d6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff8145aea9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
```
In block/blk-mq-tag.c (ffffffff8145f661)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff81461522)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff814c5d9f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff814c754b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff814d850a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff814e2810)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152475e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff826f3ecf)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff81545d38)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/tty/tty_ioctl.c (ffffffff815ddbce)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff815df0da)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff815eb47a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff815edec9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8161ec2c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff81626ac6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8163f43e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/base/node.c (ffffffff81661235)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff8169b07b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816a0b41)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a7cb3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a9a8f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_logging.c (ffffffff816bdd53)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6837)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone
```
```
In drivers/ata/libata-scsi.c (ffffffff816dd46a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff816fd998)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817171dd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8171b0ee)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff8172e283)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81754fb0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817749c8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/interface.c (ffffffff8178ae39)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff8178c863)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a766a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff817ba43c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d7727)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818439a9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff818626f7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff8186e416)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8187a589)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81885266)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff818b1f0f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7f61)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbb5e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff818feed5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c5d6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ncsi/ncsi-manage.c (ffffffff8196eac5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_add_filter
```
```
In lib/nmi_backtrace.c (ffffffff81976211)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In init/do_mounts.c (ffffffff81002a65)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009d8f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015182)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810224d5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a164)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/idt.c (ffffffff8102f153)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff81039ce4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042f23)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810436d6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81057f30)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/hpet.c (ffffffff8106aeb7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff81094d35)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In kernel/workqueue.c (ffffffff810a9ed5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810b11dc)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff819ed1fe)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810f63f1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81101c1b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff811262e6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81127a21)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff811284a8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8115e980)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/watchdog.c (ffffffff8116a04f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8116aab5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811e693b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ede03)
Location: arch/x86/include/asm/bitops.h:218
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
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff811f1fb0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff811fe6e0)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/readahead.c (ffffffff811ffb55)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/swap.c (ffffffff81202a03)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81203739)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120c111)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81210cd1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff81217d4d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/gup.c (ffffffff8122645f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122d28d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mlock.c (ffffffff81232fdb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8123474d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/rmap.c (ffffffff812400f7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8124639c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8124730a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff81247bae)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124c769)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff81257ad6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff81261849)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff812695ad)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff8126fce6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278f35)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8127b59c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81282b34)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8128a145)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e939)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:trylock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/balloon_compaction.c (ffffffff8128f9c3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff81291068)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/hmm.c (ffffffff81291e23)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff81297ed2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/pipe.c (ffffffff812a3808)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812b4933)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff812c9e0b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/splice.c (ffffffff812cf91b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812d912c)
Location: arch/x86/include/asm/bitops.h:218
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
In fs/crypto/crypto.c (ffffffff812fa7ad)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff8130a4be)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff8130dc77)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/quota/dquot.c (ffffffff813109f7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff8133688c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133cb5f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346c18)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a294)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134bfad)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8135ab78)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81367074)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff8136fea2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff813718b2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff81384dd1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8138f70e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81395118)
Location: arch/x86/include/asm/bitops.h:218
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
In fs/jbd2/commit.c (ffffffff81395b16)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397b59)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81399089)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff8139e12f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff82714b96)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ramfs/inode.c:init_ramfs_fs
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5fe2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6812)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff813c17c5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813c8e17)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff813e418b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff813ed563)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814506cb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81457475)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In block/blk-tag.c (ffffffff814858e9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-softirq.c (ffffffff8148c8b5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8148cb26)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq-tag.c (ffffffff81492f2d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff81494f42)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In block/blk-zoned.c (ffffffff814b8018)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff814f6caf)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff814f822b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff81507a5a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8151203c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a4cd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff8271deb2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff8157b1d8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/tty/tty_ioctl.c (ffffffff81616e8e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff816183f5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816246a9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff816273b1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816589ac)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816617c6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8167ab8b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/base/node.c (ffffffff8169ca05)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff816d7509)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816dce11)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3d93)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e5fb7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_logging.c (ffffffff816fa323)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff81719bba)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff8173ca33)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81756037)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81759ec1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff8176d2dd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81795595)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b5118)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/interface.c (ffffffff817cc030)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_register
```
```
In drivers/rtc/rtc-dev.c (ffffffff817cf5d3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef0ba)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81802415)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81820137)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8188dd5a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff818ae3c7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff818bf5a2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818cbd75)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818d8bf6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81907131)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cafc)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819115cb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81955992)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819949cd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff819d2981)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In init/do_mounts.c (ffffffff81002ab5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009cbf)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015782)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021b75)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a7b4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/idt.c (ffffffff810303e3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103b234)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044503)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8105dbec)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In arch/x86/kernel/hpet.c (ffffffff81070c47)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_work
```
```
In kernel/softirq.c (ffffffff8109d145)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In kernel/workqueue.c (ffffffff810b2fa5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810ba25c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a2842e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81101b61)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff8110d5bb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff811319c6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81133111)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81133d8a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/debug/debug_core.c (ffffffff8116b610)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/watchdog.c (ffffffff81176f8b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81177aac)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f7497)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811ff402)
Location: arch/x86/include/asm/bitops.h:218
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
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
```
In mm/oom_kill.c (ffffffff81203e10)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page_alloc.c (ffffffff8120d437)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/page-writeback.c (ffffffff8120efd2)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/readahead.c (ffffffff812123d5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/swap.c (ffffffff81215383)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/truncate.c (ffffffff81216009)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121ec58)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81222cfb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (ffffffff8122ac5d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/gup.c (ffffffff8123a7bd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123d1f4)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/mlock.c (ffffffff812467b0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81247ecd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/rmap.c (ffffffff812547f7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffff8125a7be)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8125b760)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffffffff8125c17e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81260cb3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8126c18f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/ksm.c (ffffffff812760ac)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/slub.c (ffffffff8127c685)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In mm/migrate.c (ffffffff81284390)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/huge_memory.c (ffffffff8128d5e5)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/khugepaged.c (ffffffff81290093)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff81296cd4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8129f0ef)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff812a2ad9)
Location: arch/x86/include/asm/bitops.h:218
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
In mm/balloon_compaction.c (ffffffff812a48e3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue
```
```
In mm/page_idle.c (ffffffff812a6088)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In mm/hmm.c (ffffffff812a6e13)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In fs/read_write.c (ffffffff812acfa2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In fs/pipe.c (ffffffff812b8958)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_steal
```
```
In fs/dcache.c (ffffffff812c9bb3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/fs-writeback.c (ffffffff812de965)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/splice.c (ffffffff812e4c8b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
```
```
In fs/buffer.c (ffffffff812ee5fc)
Location: arch/x86/include/asm/bitops.h:218
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
In fs/crypto/crypto.c (ffffffff8130fb2d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/mbcache.c (ffffffff8131fc9e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff81324b32)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_set_page_dirty
  - fs/iomap.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff81327c17)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/balloc.c (ffffffff8134db0c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8135420f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135edc8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81362457)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813640ed)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81372e38)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f4f4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffffffff81388332)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/resize.c (ffffffff81389d79)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
```
```
In fs/ext4/super.c (ffffffff8139d8c1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813a8095)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ade88)
Location: arch/x86/include/asm/bitops.h:218
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
In fs/jbd2/commit.c (ffffffff813ae862)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b08df)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b1df9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/jbd2/journal.c (ffffffff813b6e9f)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ramfs/inode.c (ffffffff828cbfef)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ramfs/inode.c:init_ramfs_fs
```
```
In fs/hugetlbfs/inode.c (ffffffff813bea08)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfd62)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
```
In fs/fuse/dev.c (ffffffff813dae95)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/file.c (ffffffff813e2197)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_page_mkwrite
```
```
In security/keys/key.c (ffffffff813fe97b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81408da2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8146d6ab)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81474965)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In block/blk-core.c (ffffffff8149af48)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814ace4d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814c347b)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff814cbb08)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff8150b0ef)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/sbitmap.c (ffffffff8150c6eb)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_get_word
```
```
In drivers/gpio/gpiolib.c (ffffffff8151c231)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81527760)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571ddd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/acpi/tables.c (ffffffff828d5edd)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815939c8)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a575)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8163408e)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff816355c5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81641b99)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffff81644f20)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816760bc)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8167fe78)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8169a4d1)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/base/node.c (ffffffff816bd255)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff816f93d9)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816ff161)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81707233)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81709347)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81711059)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712cf5)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_logging.c (ffffffff8171cd63)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c4ba)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81760f43)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff8177a523)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8177e441)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff8179192d)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bbb17)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db668)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/rtc/dev.c (ffffffff817f5fd3)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181af8a)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff8182e705)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184bfe7)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818aebea)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffffffff818d2647)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff818e83c2)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818f7215)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819053e6)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81934d21)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ae3c)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193fde4)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a472)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb2a0)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81a0c001)
Location: arch/x86/include/asm/bitops.h:218
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/amd/ibs.c (ffffffff8100a19b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016e0b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024f65)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c5cb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff810321bf)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103d81d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046ad3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81060f7e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/softirq.c (ffffffff810a1115)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b8b95)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c0166)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a98c1f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110a37a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81116cc1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c548)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113dca9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff811783dc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff81183e4b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81184912)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120f328)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff8121b253)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8121eb53)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff81224da5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8122e335)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8123a8cd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff812587e7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125a0ee)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff81273897)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a9588a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812a39b1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812ace79)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812b41fa)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812b9b5d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd055)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8130f13e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134b314)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff8134f769)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff813dc459)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff81406a75)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
```
```
In security/keys/key.c (ffffffff8142afcb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81435921)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149addf)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a2685)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814c9078)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814db171)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814f1b7b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff814fa7a8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff8153981f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff8154a511)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81556a01)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffffffff828efd33)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815c4ab8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e365)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8166813e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff816698f5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816760f8)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816abecc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816b7296)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816d2e83)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/base/node.c (ffffffff816f8020)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_memory_block_under_nodes
```
```
In drivers/nvdimm/region.c (ffffffff81732e67)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81738f04)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8174249f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744b0d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c479)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e815)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_logging.c (ffffffff81758325)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer
```
```
In drivers/ata/libata-scsi.c (ffffffff81777fad)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff8179ebd8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817b8064)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817bc9c1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817d09b6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fe0f2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181c07c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c460)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f362)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d1d0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81870c15)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188f117)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818fa7c3)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff81937bd2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff81956925)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819665c6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81998af0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f1c4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a42dd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff819f47c6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39cd9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81a7b961)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025545)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce9b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032a7f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103dfdd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047253)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810617ee)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a4570)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/softirq.c (ffffffff810a76d5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810bf0b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c6526)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81ad056f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111674a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81123091)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81148158)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114985c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff8118425c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff8118fcc4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81190792)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121c805)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff81228d13)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8122c5f3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff81232b35)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8123c4c5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff81248bdd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff81266cb7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8126859e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff81282707)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81acd16d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812b4eb1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812bda79)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812c5b0c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812cbe36)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8130f545)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8132209e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813635c4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff81367a79)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff813f64a9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8141ff45)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff81444d1b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff8144f6c1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814b501f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bd355)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814e2268)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814f45a1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8150b15b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81518708)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff8155a63f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff8156a3a1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81578021)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffffffff828f8ea4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815e5cf8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660845)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8168a88e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8168be15)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81698898)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816cec4c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816d9e46)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816f6d63)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81756a73)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8175cc50)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817664ae)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768c4d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff817705f9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817729c5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8179beed)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817c2668)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817e8835)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817ed1e1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818018d2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182ef42)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d43c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186de04)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870d02)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188efc3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff818a2a05)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c10f7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8192c903)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff8196aa92)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8198cdc5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199d056)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff819cf60f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5d74)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819daefd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b476)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70869)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81ab2cc1)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019349)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029520)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ee4c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff82ccf1c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810410ad)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a079)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810675ef)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810ab840)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810aede5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c62b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81bc8eef)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81122374)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811261c9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112f6c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81157f98)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81159660)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/debug/debug_core.c (ffffffff811982dc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/watchdog.c (ffffffff811a488e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811a533d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81245a7b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_take_insn_slot
```
```
In mm/oom_kill.c (ffffffff81256bba)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81259f03)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff81260017)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8126ad2e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff812768ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/mlock.c (ffffffff81296f07)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81298b5e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b486d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81bc5b62)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812ea364)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812f3279)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812fb532)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81301fdb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/fs-writeback.c (ffffffff8134eca2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/buffer.c (ffffffff8135d8fb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813a9ec4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff813b1eba)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/jbd2/revoke.c (ffffffff81443a39)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8146ec85)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff81495f8e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a0e70)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff815145bf)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d715)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81540f28)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81554c21)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156c0bb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81578a8a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff815e3f7f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/nmi_backtrace.c (ffffffff815ed561)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81610451)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8161ccc3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff82d0f7af)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff8169065b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710845)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c83e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dea5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff8174ac08)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81783b0c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8178dbd6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817affb2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81816063)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8181c550)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81826871)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ab2d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81832ee9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81835e65)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff81868b6d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff81880495)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8188d143)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818b7d80)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818bca01)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818d2202)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190309c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191fedc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941f12)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944d42)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195dc73)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81973e15)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81992e77)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff819fffd6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81a3e485)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a64635)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a76296)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81a83af6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81abb862)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2250)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8057)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d945)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b693d7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bac65a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810186af)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028a98)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fc5c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff82fbb087)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8104100d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049519)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067bf4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106922f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a70c0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810aa5b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c1315)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81c41cdf)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111e33b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff81121db9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112b5c7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81154088)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8115561c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/debug/debug_core.c (ffffffff811956bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/watchdog.c (ffffffff811a192e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81be501b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8124ff7b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_take_insn_slot
```
```
In mm/filemap.c (ffffffff8125a801)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812617ca)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812656b7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff8126aa2c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff8127576e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff812811ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/mlock.c (ffffffff812a1f48)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812a3cde)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f553e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812fe9d9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8130738f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8130e70e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/fs-writeback.c (ffffffff8135bb22)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/buffer.c (ffffffff8136b4eb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff813bb514)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff813c349c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/mballoc.c (ffffffff8141c044)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff8145fb19)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8148941f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff814b39ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814be820)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff8153169f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a585)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8155dbb8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff8157138c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff81586deb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81595638)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff816084af)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/nmi_backtrace.c (ffffffff81611d21)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff816366cd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a092)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff816433f3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff82ffd230)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff816ae37b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d425)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff817589ae)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81759e05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81766378)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8179b05c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff817b9946)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817c4b35)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff818251f3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8182b5a0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837391)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b7ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81843aea)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81846985)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff8187797d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff8188ed45)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8189b3c6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818c6690)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818c9711)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818dc5e2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190b965)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819275d8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81948262)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194ad82)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964663)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81975efd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81978d15)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996097)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff81a00016)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81a41235)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a6c775)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7f006)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81a8d626)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7442)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc80)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3eb7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c215)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77e07)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bbecca)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81bc2bdc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810199d2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a625)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103076c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff831c58ff)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810429fd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bfeb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067fff)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81069c25)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a8160)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810ab80b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c2cf5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81c33c4f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111e64b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff81122139)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8112b893)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff81137e7d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811554f9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81156bb3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog_hld.c (ffffffff81bd6e0b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81256dde)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff8125f05e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81264f91)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8126a1b3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff8126fc0c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff8127aa8e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8128631d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/mlock.c (ffffffff812a77d8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812a946e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fbb95)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff81305649)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8130db05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff81314bea)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/fs-writeback.c (ffffffff81362732)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/buffer.c (ffffffff81371d8b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io_uring.c (ffffffff81391e90)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In fs/io-wq.c (ffffffff813a1fc8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/iomap/buffered-io.c (ffffffff813c2633)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff813c9a82)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/mballoc.c (ffffffff814222bb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff814651f9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8148ecaf)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff814b981e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c4b4d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff81539b2f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542c45)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81566418)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff815793bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff8157e1b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-cgroup.c (ffffffff8158dc2a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff8159c289)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff815eb10f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/nmi_backtrace.c (ffffffff815f5401)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81619d1d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dce2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff81626213)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff83208825)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff816908db)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710805)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8173c84e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8173dca5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749fc6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783b3b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff8179caf6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/lightnvm/core.c (ffffffff817a7997)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81808583)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8180e8c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a541)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ea0d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81826c9a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818297e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff8185a15d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff818714d7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8187e056)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff818a9a7f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818ad041)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff818bf7c4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ec9ae)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190ac98)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bbc2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e8c2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948a83)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff8195a0c7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff8195c205)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197ae67)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff819e6576)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81a25e95)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81a54f05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a67ea6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81a76196)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2465)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8ff0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abef79)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e75)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66912)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81bb08b0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e6f2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ec35)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103563c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff832a6677)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff81048d6d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810533ec)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107247f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81074335)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810b9c10)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810bd25b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810d5835)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffff81d5260f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8113eaf2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811426e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff8114c383)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff8115abd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8117988e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8117b946)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog_hld.c (ffffffff81cb3f19)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81292b6e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff8129b7bd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812a17c4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812a6e46)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
```
```
In mm/swap.c (ffffffff812aced8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_inactive_or_unevictable
```
```
In mm/vmscan.c (ffffffff812b8aee)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff812c562c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/mlock.c (ffffffff812e8d80)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff812ef639)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/huge_memory.c (ffffffff8134598e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff8134f4a9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff813589fb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff81360c6a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/fs-writeback.c (ffffffff813b0f32)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/buffer.c (ffffffff813c0dab)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/io-wq.c (ffffffff813f1373)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_cancel
  - fs/io-wq.c:io_wq_worker_wake
```
```
In fs/quota/dquot.c (ffffffff8141a338)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/mballoc.c (ffffffff814759f4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff814bab79)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff814e671e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8151204e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d52c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff8159849f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a3165)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff815ca7e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff815de5fc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff815e38b1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/blk-cgroup.c (ffffffff815f369a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff816048bd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff8165760f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/ubsan.c (ffffffff816599d5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
In lib/nmi_backtrace.c (ffffffff81662871)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff81688ffd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d302)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
```
```
In drivers/pwm/sysfs.c (ffffffff81695a53)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff832f09c0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff8170634b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d1f4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff817be235)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff817cb621)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a55b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff818257c6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81892d53)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81898ea1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4a81)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a909d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff818b25e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b5345)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-sata.c (ffffffff818e8c4d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_sas_allocate_tag
```
```
In drivers/net/phy/phy.c (ffffffff81901bb7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff8190f840)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff8193e98f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff819420e1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff81955e34)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819890cd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab348)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ced82)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1af2)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819eda83)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff819ff897)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81a01a15)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81a05f3e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a2423a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/core/dev.c (ffffffff81a96aa6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81adabf5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81b0dc15)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b218d6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81b307d6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f2e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763f0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7caa5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde49a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e4aa)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81c7e8d0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81c81728)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81c83d0b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102121f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81033ea5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b46c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83455891)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff810520ea)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ee8c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8108062f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81082b6d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810d0710)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810d439b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810eebc5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81f22ab6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81162168)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff8116623c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff81171cfd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff81184497)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee2d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811b0fe9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog_hld.c (ffffffff81e64dc7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e858d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff812f4207)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff812f94c4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812ff061)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff8131458e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/mlock.c (ffffffff8134c06f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81352ab1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
```
```
In mm/huge_memory.c (ffffffff813bbacb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff813c7707)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff813d2890)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff813dc383)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/fs-writeback.c (ffffffff81435dc6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
```
```
In fs/buffer.c (ffffffff8144508c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/quota/dquot.c (ffffffff81493328)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
```
```
In fs/ext4/mballoc.c (ffffffff814f7cd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff81544a19)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff815744ae)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff815a44be)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b08dc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff8163cd3f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff816499a5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81675d68)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff8168c751)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff81692b11)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/partitions/core.c (ffffffff81e8c64c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In block/blk-cgroup.c (ffffffff816a4caa)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff816b804d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In io_uring/io-wq.c (ffffffff816da1a4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
```
```
In lib/irq_poll.c (ffffffff8176ef1f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In lib/ubsan.c (ffffffff81772005)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
In lib/nmi_backtrace.c (ffffffff8177c6b8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/gpio/gpiolib.c (ffffffff817a63fd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abeba)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff817b6813)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff834a894c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff818344ab)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c52f0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff818fa515)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81908e55)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a2c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff81965396)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff819dd007)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff819e2de9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eea65)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f2fe7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd6aa)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a01fae)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81a534e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81a62e1b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81a969c7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81a99fb3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81aaf08d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae2ee1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b090f8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30b05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b340c3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b543a3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81b66e0a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81b69937)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm-zone.c (ffffffff81b6dc77)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8d93a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/core/dev.c (ffffffff81c0d98c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81c5baa5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81c94ff5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ca9f56)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81cbb673)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe96a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05bcc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c9a0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81d752b4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbcda)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81e24066)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81e271b8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81e29ef0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025bff)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b935)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043c3c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83e737c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8105f92a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d5fc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092fea)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8109562d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810eeff0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810f322b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff8110feb5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/build_utility.c (ffffffff820cd406)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff81195bd8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff8119a3ac)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811a83bd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811bf741)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef5ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811f1c29)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog_hld.c (ffffffff812481f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8135222d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff8135fa39)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81363244)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff813697e6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff813886ce)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/shmem.c (ffffffff8138f78c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/mlock.c (ffffffff813c4c2f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813c6b89)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143e304)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144b6f7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8145801c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff81463350)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/fs-writeback.c (ffffffff814bf945)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff814d3450)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/quota/dquot.c (ffffffff81526fe8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/mballoc.c (ffffffff81592290)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff815e3b29)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff81619d3e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8164e581)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b2bc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff816f465f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702975)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff81731d28)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/genhd.c (ffffffff81750f91)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
```
```
In block/partitions/core.c (ffffffff81754518)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81763a50)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81778668)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff817a6234)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
```
```
In lib/irq_poll.c (ffffffff8189e94f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff818a20f9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
In drivers/gpio/gpiolib.c (ffffffff818bae8d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c47fa)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff818d1063)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff83edf75d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff81968f48)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07876)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15bd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a535b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a63445)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aad931)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/iommu.c (ffffffff81ace7c6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81b5875d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81b5ea39)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c175)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70d57)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7babd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b8066e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81bdc8b6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81bee0cb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81c19577)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e513)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81c36b8d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6e981)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98dec)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5425)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc90a3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced123)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81d02678)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81d05555)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d0a162)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d29e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/core/dev.c (ffffffff81dc10fc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81e11ed5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81e50ad5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e66fe6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81e79c03)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81ec387c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecad1c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed23d1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9cdeb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff81ff8111)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
```
```
In net/mptcp/subflow.c (ffffffff81ffe928)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82002000)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff82039188)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81025b1f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103ba15)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043d50)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff83695281)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8106107a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095f3a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81098550)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810fafa0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff810ff56b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff8111c4b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (ffffffff8114301e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff82151886)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff811a7586)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811ac0d0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811ba08d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811d2221)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff81203d83)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff812063d7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog.c (ffffffff8125e8ec)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_hardlockup_check
```
```
In kernel/bpf/cpumask.c (ffffffff8135d825)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In kernel/events/uprobes.c (ffffffff8138343d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff81390a01)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff81395674)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff8139b983)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff813ba85e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/shmem.c (ffffffff813bf636)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/mlock.c (ffffffff813f919f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813fb016)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff81473b04)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480f45)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8148dd63)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff81498fed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/fs-writeback.c (ffffffff814f4a45)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8150a6e0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/quota/dquot.c (ffffffff8155f4bb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/mballoc.c (ffffffff815c9367)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff8161b2e9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff81651eee)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff81686de1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81693bb9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff8172e77f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173c9a5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff8176e0a8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81787604)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff8178d561)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:blk_mark_disk_dead
```
```
In block/partitions/core.c (ffffffff81790638)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a2afd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff817b81a8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff817e7194)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
```
```
In lib/irq_poll.c (ffffffff818e0f1f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff818e4529)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
In drivers/gpio/gpiolib.c (ffffffff818fdf8d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819078ca)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff81914053)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff837051ed)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff819af538)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50706)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec10)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81a9da05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aadb05)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af91c4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b01e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/iommu/iommu.c (ffffffff81b1d166)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81babccd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81bb1fe9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf955)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc4587)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf7e0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd46ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81c33c76)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81c465fb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81c80597)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c853fb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81c9de7d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd5f94)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00187)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d0b5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30dc3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55e63)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81d6b5b9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e635)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d7329b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9650e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81dd5d64)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
```
In net/core/dev.c (ffffffff81e30d4c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81e857e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81eac2e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec2da6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f03)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81f21abc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29850)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f310c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd8af)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff82074641)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff82079da9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff8207dc10)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/handshake/request.c (ffffffff82093834)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/nmi_backtrace.c (ffffffff820b7498)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102bc7f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_register
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81041ed5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a250)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/idt.c (ffffffff838c51c1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8106814a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d47a)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8109faf0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff81104440)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In kernel/softirq.c (ffffffff81108c1b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff81126c25)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (ffffffff8114e4ee)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/build_utility.c (ffffffff822346c6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff811b70e6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffffffff811bbcd0)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/irq/matrix.c (ffffffff811c9f4d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/livepatch/transition.c (ffffffff811e6ea1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a343)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8121d5e7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/bpf/cpumask.c (ffffffff813865c5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In kernel/events/uprobes.c (ffffffff813ac857)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/filemap.c (ffffffff813ba681)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:wake_page_function
```
```
In mm/oom_kill.c (ffffffff813bf434)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff813c43f5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:folio_mark_dirty
```
```
In mm/vmscan.c (ffffffff813e397e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/shmem.c (ffffffff813ea66e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/mlock.c (ffffffff81424d4f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81426c66)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a3014)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aff35)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff814bd6d6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/memory-failure.c (ffffffff814c86b6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
```
```
In fs/fs-writeback.c (ffffffff81529155)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8153f690)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
```
In fs/quota/dquot.c (ffffffff81595bab)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
  - fs/quota/dquot.c:dquot_mark_dquot_dirty
```
```
In fs/ext4/mballoc.c (ffffffff81602147)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/jbd2/revoke.c (ffffffff81654209)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8168b4fe)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff816c32f1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d01b9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:getoptions
```
```
In security/integrity/ima/ima_fs.c (ffffffff8176f0df)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177d7a5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_set_key
```
```
In block/blk-core.c (ffffffff817b02d8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff817c9ce1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/genhd.c (ffffffff817cfdc1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:__blk_mark_disk_dead
```
```
In block/partitions/core.c (ffffffff817d3ed8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e663d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff817fca68)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
  - block/blk-zoned.c:blk_req_zone_write_trylock
```
```
In io_uring/io-wq.c (ffffffff8182cf54)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_cancel
  - io_uring/io-wq.c:io_wq_worker_wake
```
```
In lib/irq_poll.c (ffffffff81927a8f)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
  - lib/irq_poll.c:irq_poll_sched
```
```
In lib/ubsan.c (ffffffff8192b529)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
In drivers/gpio/gpiolib.c (ffffffff819455fd)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950d52)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/pwm/sysfs.c (ffffffff8195bf93)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/acpi/tables.c (ffffffff8393871d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_initrd_scan
  - drivers/acpi/tables.c:acpi_table_initrd_override
```
```
In drivers/acpi/ec.c (ffffffff819f99e8)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c3d6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1347)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ldisc.c (ffffffff81af04f5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_open
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b00735)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c7e4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_status
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70b4e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/iommu/iommu.c (ffffffff81b736e6)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_group
```
```
In drivers/nvdimm/region.c (ffffffff81c0000d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81c064d9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c140d5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c191a7)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81c24440)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2935e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_done_internal
```
```
In drivers/net/phy/phy.c (ffffffff81ce8e66)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/tun.c (ffffffff81cfbf0b)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81d34f67)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81d39dfb)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/core/port.c (ffffffff81d52a2d)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8af74)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5c20)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2f95)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6d93)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0cd73)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md.c (ffffffff81e215de)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/md-bitmap.c (ffffffff81e263fc)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81e2a3de)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e16e)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81e8df26)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
```
In net/core/dev.c (ffffffff81eef2e5)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/netpoll.c (ffffffff81f47715)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
```
```
In net/sched/sch_generic.c (ffffffff81f6ed75)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f86188)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ethtool/ioctl.c (ffffffff81f99a63)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5a4c)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee3c9)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7039)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/udp.c (ffffffff820081f3)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc754)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/mptcp/protocol.c (ffffffff821489e1)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff8214f209)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/handshake/request.c (ffffffff8216a0e4)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
```
```
In lib/nmi_backtrace.c (ffffffff82191648)
Location: include/asm-generic/bitops/instrumented-atomic.h:68
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int test_and_set_bit(unsigned int nr, volatile long unsigned int *p);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010085f40)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (ffff8000100884d8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:do_sve_acc
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a4488)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
  - arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx
```
```
In arch/arm64/mm/flush.c (ffff8000100adcc4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In virt/kvm/arm/arm.c (ffff8000100c740c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_irq_line
```
```
In kernel/cpu.c (ffff8000100fa220)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In kernel/softirq.c (ffff8000100fe980)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffff80001011cbb0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffff800010124fbc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffff800010da2450)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffff8000101788a0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (ffff80001017d630)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/time/tick-broadcast.c (ffff8000101b39f4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffff8000101b5f70)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffff8000101f9b4c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In kernel/watchdog.c (ffff800010207430)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (ffff8000102a83f0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/oom_kill.c (ffff8000102b7150)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bc068)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffff8000102c2b20)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffff8000102cd690)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffff8000102dda28)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mlock.c (ffff8000102fde40)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffff8000102ffed4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In mm/page_alloc.c (ffff80001031ac9c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffff800010da0210)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffff800010356204)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffff80001035ef4c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff8000103688ac)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffff80001036f3d0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffff8000103c6f3c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In fs/buffer.c (ffff8000103daddc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffff80001042a2a4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In fs/quota/dquot.c (ffff80001043292c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
Direct callers:
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffff8000104d2574)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffff800010502860)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffff80001052df40)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffff80001053acb8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffff8000105adb28)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b60e0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In block/blk-core.c (ffff8000105e0e14)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffff8000105f4258)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffff80001060eaf4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffff8000106200c8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffff800010667bd8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473ce0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/gpio/gpiolib.c (ffff8000106c18e4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffff8000106d9c34)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffff80001147bf94)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffff800010771074)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/dma/amba-pl08x.c (ffff800010802178)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108052c0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor.c (ffff800010806534)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808884)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler
```
```
In drivers/dma/mxs-dma.c (ffff80001080a138)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080cffc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082aad4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/xen/events/events_2l.c (ffff800010832e04)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
  - drivers/xen/events/events_2l.c:evtchn_2l_test_and_set_mask
```
```
In drivers/xen/events/events_fifo.c (ffff800010833784)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_test_and_set_mask
```
```
In drivers/tty/tty_ioctl.c (ffff800010859650)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffff80001085be88)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffff80001086e8c8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffff8000108732fc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffff8000108b90cc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffff8000108c508c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d11e8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d401c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_bitmap_alloc
```
```
In drivers/lightnvm/core.c (ffff8000108e0bbc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffff800010957f10)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffff80001095e470)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffff800010967588)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a084)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffff8000109739cc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffff800010977860)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6bb4)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/spi/spi.c (ffff8000109c7b18)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/tun.c (ffff8000109dceb8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fd74c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/usb/core/hub.c (ffff800010a17e94)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffff800010a1cc44)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffff800010a35ce0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6cfc0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c880)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab172c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab48c8)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6d68)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfeec)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffff800010af8a20)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1f548)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/of/platform.c (ffff800010b6da3c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_bus_create
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In drivers/perf/arm-cci.c (ffff800010b91140)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b92dfc)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99a8c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
```
```
In net/core/dev.c (ffff800010bcda0c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (ffff800010bf3918)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffff800010c11048)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffff800010c37fd0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4c0d0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffff800010c82a64)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffff800010c887f0)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e298)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffff800010cea02c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39d4c)
Location: include/asm-generic/bitops/atomic.h:32
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
**Symbols:**

```
ffff80001042eb40-ffff80001042ebb8: test_and_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006cfac)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d9420)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_enable
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_alloc_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_reserve_pe
```
```
In arch/powerpc/xmon/xmon.c (c000000000110744)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_ras.c (c000000000120c8c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_hmi_handler
```
```
In kernel/cpu.c (c00000000013e120)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In kernel/softirq.c (c000000000145b48)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (c000000000163d80)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
  - kernel/workqueue.c:try_to_grab_pending
```
```
In kernel/task_work.c (c00000000016ec20)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (c000000000ee38ec)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (c0000000001d2790)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/resend.c (c0000000001d820c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/time/tick-broadcast.c (c0000000002192f0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (c00000000021b9a4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (c0000000002713a0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In kernel/watchdog.c (c000000000283a88)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/uprobes.c (c00000000035b998)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (c00000000036e170)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (c0000000003737e8)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (c00000000037cc30)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (c00000000038b108)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (c00000000039d690)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In mm/mlock.c (c0000000003c9480)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (c0000000003cb6dc)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In mm/page_alloc.c (c0000000003ee484)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (c000000000eece40)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (c00000000043c690)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (c000000000449a3c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (c000000000456854)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (c000000000460fc8)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (c0000000004c4758)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (c0000000004e3db8)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (c00000000053ab94)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (c0000000005404e0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (c00000000060bd10)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (c000000000646754)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (c000000000679e8c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (c0000000006892b0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (c00000000072c5c0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (c00000000073a0d0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In block/blk-core.c (c000000000771748)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (c00000000078ba54)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (c0000000007ac124)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (c0000000007bf7a4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (c00000000081cfa0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (c000000000839f24)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (c000000000851724)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6360)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (c0000000008f896c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (c0000000008fb2d4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (c00000000090ee40)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (c000000000913e88)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (c000000000959e84)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (c00000000096bd04)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (c00000000097498c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (c000000000a062d4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (c000000000a103b4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e584)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (c000000000a227b0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (c000000000a2d530)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c000000000a303e0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (c000000000a6d0d8)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/spi/spi.c (c000000000a88624)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/tun.c (c000000000aa2970)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (c000000000ad0d88)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad60a0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (c000000000af3134)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b40310)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68fd0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (c000000000b945fc)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c000000000b98a68)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99d74)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc807c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (c000000000be42a0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c10eb4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/of/platform.c (c000000000c47e48)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In net/core/dev.c (c000000000ca5a00)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__netif_schedule
```
```
In net/core/link_watch.c (c000000000cd8bf4)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (c000000000cfd50c)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (c000000000d301d0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d48178)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (c000000000d8d410)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (c000000000d95b90)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ccac)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (c000000000e0d880)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ad80)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (c000000000ecf0d0)
Location: arch/powerpc/include/asm/bitops.h:141
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba11a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_pte
```
```
In kernel/cpu.c (ffffffe00000479e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/softirq.c (ffffffe0000c6d08)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffe0000d8812)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/task_work.c (ffffffe0000dcee4)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In kernel/sched/wait_bit.c (ffffffe0008c5a00)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffe000113276)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/time/tick-sched.c (ffffffe00013c074)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/watchdog.c (ffffffe000169b72)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/oom_kill.c (ffffffe0001dbe50)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page-writeback.c (ffffffe0001de17a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffe0001e3e20)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/backing-dev.c (ffffffe0001f5958)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mlock.c (ffffffe00020c542)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffe00020d732)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In mm/shuffle.c (ffffffe000047560)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/memcontrol.c (ffffffe0002466e4)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/fs-writeback.c (ffffffe0002841ba)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In fs/buffer.c (ffffffe000293806)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffe0002c84a4)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In fs/quota/dquot.c (ffffffe0002ce958)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffe000349606)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffe00036f82e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffe00038f68a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffe000398c10)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffe0003f5828)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fce5c)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In block/blk-core.c (ffffffe000421f9c)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffe000432350)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffe000446ed2)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffe000452788)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffe000492ff0)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a4924)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffe0004b292a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fbb0)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffe000534062)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffe0005354c8)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffe00054199a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffe000544e36)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffe0005695da)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/lightnvm/core.c (ffffffe0005764f8)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e2c)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffe0005cc3dc)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d330c)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5a1a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc7e8)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de62e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffe0006055a0)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/spi/spi.c (ffffffe00061828e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/tun.c (ffffffe000627bd6)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffe00063cc26)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffe0006409a4)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffe000652b8e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000681c36)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a1654)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b91b6)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbdee)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc8da)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-of.c:of_i2c_register_devices
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7968)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffe0006e968c)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/of/platform.c (ffffffe0007222e6)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - drivers/of/platform.c:of_platform_device_create_pdata
```
```
In net/core/dev.c (ffffffe000755632)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:netif_schedule_queue
```
```
In net/core/link_watch.c (ffffffe0007750ca)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffe00078d0e2)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffe0007a97ce)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b971a)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_attachskb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3f9e)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9bce)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee6c2)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffe000837be4)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875b88)
Location: arch/riscv/include/asm/bitops.h:72
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In arch/x86/events/amd/ibs.c (ffffffff8100a58b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810177b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810256a5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cffb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032bdf)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103e15d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810473d3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106136e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8109de90)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/softirq.c (ffffffff810a0ff5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b9425)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c08a6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a6f3df)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110ed2a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff8111b671)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff81140778)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff81141e7c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff8117c87c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff811882e4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81188db2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81214e55)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff81221363)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81224c43)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff8122b185)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81234b15)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8124122d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff8125f307)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff81260bee)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127ad57)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a6bfdd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812ad491)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b6059)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812be0ec)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c4416)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81307b25)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8131a67e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8135bba4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff81360059)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff813eea89)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff81418525)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8143d2fb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81447ca1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814ad5ff)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5935)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814da848)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814ecb81)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8150373b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81510ce8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff81552c1f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff8155fb61)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8156ce31)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffffffff828e1c10)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815d7be8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816266b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8165030e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81651895)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165e2f8)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8169469c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8169f896)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816bc553)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff8170b163)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81711340)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171ab9e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d33d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81724ce9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817270b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/nvme/host/core.c (ffffffff81743684)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81760fdd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81787138)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817a0c15)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817a55c1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817b9cb2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e7322)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834e43)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81848885)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81865817)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff818cc903)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff8190aa62)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8192cc35)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193cec6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff8196f47f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81975be4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ad6d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff819cab06)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0fef9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81a51b11)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016be5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/kernel/idt.c (ffffffff8102251f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8102d971)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036557)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff810517ce)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8108c8b0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/softirq.c (ffffffff8108fa15)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810a7d65)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810af0a6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81a2b80f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff810ffa6f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff8110c6e1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff811334f8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff811351dc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff8116fa5c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff8117b424)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8117bef2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81207bc5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff81214513)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81217df3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff8121e295)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81227b85)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8123422d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff81251727)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125300e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126cc37)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81a28524)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff8129e448)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812a7249)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812af209)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812b5456)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff812f8745)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8130b21e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8134c844)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff81350cf9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff813df509)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff81408fa5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8142dd6b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff814386f1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff8149e01f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a6355)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814cb1f8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814dd0d1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814f3bfb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81501008)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff81542f2f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff815509b1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/acpi/ec.c (ffffffff815c17a8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/acpi/nfit/core.c (ffffffff815f915e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_ars_rescan
  - drivers/acpi/nfit/core.c:scrub_show
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ad35)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8163075e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff81631cd5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163e678)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff8167208c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff8167d286)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816debe3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816e4dc0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f3ffe)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f679d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe119)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff817004e5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/nvme/host/core.c (ffffffff81725314)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff81740e3d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff81766a88)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff81792a55)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81797081)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817ab6e2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca98c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc4d3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff8180fee5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182e4c7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184eb60)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_isr
```
```
In drivers/hv/connection.c (ffffffff81850026)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_on_event
```
```
In net/core/dev.c (ffffffff81886993)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff818c4652)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff818e6735)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f69c6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff81928f4f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f6a4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193482d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff819878f6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cccb9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81a0ec11)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017775)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025505)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce5b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff81032a3f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103df9d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047213)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff8106179e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff8109de40)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/softirq.c (ffffffff810a0fa5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810b8985)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810bfdf6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81adb7ef)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8110cc1a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81119561)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e628)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8113fd2c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff8117a64c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff811860b4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81186b82)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81212bf5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff8121f103)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff812229e3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff81228f25)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff812328b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8123efcd)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff8125d0a7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8125e98e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff81278af7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81ad83ed)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812ab2a1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812b3e69)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812bbefc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c2226)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81305915)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff8131814e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff81359674)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff8135db29)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff813ebe09)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff814146c5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8143949b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff81443d41)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814a969f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b19c5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814d68d8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff814e8c11)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff814ff7cb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff8150cd78)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff8154e95f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff8155e6d1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff8156bd71)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffffffff828f4aa0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815d9fd8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654685)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff8167e6ce)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8167fc55)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168c6d8)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816c290c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816cdb06)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816eaa23)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff81749f33)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81750110)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8175996e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c10d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff81763ab9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765e85)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81790d6d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817b74e8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817dd6b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817e2061)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff817f6752)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81823dc2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff818422bc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81861f94)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864e92)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884473)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff81897eb5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b65a7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8191d903)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff8195ba92)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff8197ddc5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198e056)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199fc7a)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a72bf)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819abbb9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
```
```
In net/ipv4/tcp_output.c (ffffffff819d9c4f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819e03b4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e553d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35586)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a979)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81abdf01)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_add
  - arch/x86/events/amd/ibs.c:perf_ibs_stop
```
```
In arch/x86/events/intel/uncore.c (ffffffff810179b5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f65)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dc4b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In arch/x86/kernel/idt.c (ffffffff8103399f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:alloc_intr_gate
```
```
In arch/x86/kernel/process.c (ffffffff8103f0e0)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048613)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/perfctr-watchdog.c (ffffffff81062d4e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_evntsel_nmi
  - arch/x86/kernel/cpu/perfctr-watchdog.c:reserve_perfctr_nmi
```
```
In kernel/cpu.c (ffffffff810a5d30)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/softirq.c (ffffffff810a8f25)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In kernel/workqueue.c (ffffffff810c1105)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_rcu_work
  - kernel/workqueue.c:queue_delayed_work_on
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:queue_work_on
```
```
In kernel/task_work.c (ffffffff810c82d6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/wait_bit.c (ffffffff81ae7d8f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
```
```
In kernel/irq/handle.c (ffffffff8111817c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/matrix.c (ffffffff81124c71)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_assign
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b136)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (ffffffff8114c85c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/debug/debug_core.c (ffffffff8118805c)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/watchdog.c (ffffffff81193a04)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811944d2)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81221b72)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/oom_kill.c (ffffffff8122e153)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffffffff81231bc3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:set_page_dirty
  - mm/page-writeback.c:__set_page_dirty_no_writeback
```
```
In mm/swap.c (ffffffff812382e5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81241d75)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/backing-dev.c (ffffffff8124e71d)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/mlock.c (ffffffff8126caa7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
```
```
In mm/mmap.c (ffffffff8126e35e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff812886e7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/page_alloc.c:set_hwpoison_free_buddy_page
```
```
In mm/shuffle.c (ffffffff81ae48a8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/huge_memory.c (ffffffff812bb5f1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff812c42fb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff812cc6c9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812d2cb6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81316c85)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_start_writeback
```
```
In fs/buffer.c (ffffffff81329d6e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/iomap/buffered-io.c (ffffffff8136cd74)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
```
In fs/quota/dquot.c (ffffffff813713b7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/jbd2/revoke.c (ffffffff814017a9)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_cancel_revoke
```
```
In fs/fuse/dev.c (ffffffff8142af35)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
```
```
In security/keys/key.c (ffffffff8145068b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
```
```
In security/keys/trusted.c (ffffffff8145b071)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In security/integrity/ima/ima_fs.c (ffffffff814c202f)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - security/integrity/ima/ima_fs.c:ima_open_policy
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca445)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In block/blk-core.c (ffffffff814ef4e8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_flag_test_and_set
```
```
In block/blk-mq-tag.c (ffffffff81501bb1)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-cgroup.c (ffffffff8151899b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
```
```
In block/blk-zoned.c (ffffffff81526458)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - block/blk-zoned.c:__blk_req_zone_write_lock
```
```
In lib/irq_poll.c (ffffffff815687af)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_disable
```
```
In drivers/gpio/gpiolib.c (ffffffff81578561)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_request_commit
```
```
In drivers/pwm/sysfs.c (ffffffff81586271)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
```
In drivers/acpi/tables.c (ffffffff828f9ef8)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
  - drivers/acpi/tables.c:acpi_os_physical_table_override
```
```
In drivers/acpi/ec.c (ffffffff815f3e98)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166ede5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
```
```
In drivers/tty/tty_ioctl.c (ffffffff81698d2e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_throttle
```
```
In drivers/tty/tty_ldisc.c (ffffffff8169a2a5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a6cd8)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff816dcedc)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/iommu/iommu.c (ffffffff816e8046)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81705263)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
```
In drivers/nvdimm/region.c (ffffffff817653b3)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8176b590)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_free_slot
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81774e8e)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (ffffffff817777ad)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f119)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781515)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/ata/libata-scsi.c (ffffffff817aabad)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_allocate_tag
```
```
In drivers/net/tun.c (ffffffff817cf58b)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/usb/core/hub.c (ffffffff817f7985)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817fc497)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/core/port.c (ffffffff81810992)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183f842)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c6ec)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d1f4)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880142)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189ff33)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/md/md-bitmap.c (ffffffff818b40a5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d2857)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In net/core/dev.c (ffffffff8193ee13)
Location: include/asm-generic/bitops-instrumented.h:141
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
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/netpoll.c (ffffffff8197de82)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/sched/sch_generic.c (ffffffff819a06f5)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b08f6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/tcp_output.c (ffffffff819e38af)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea072)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef1eb)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40ee6)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a871b7)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In lib/nmi_backtrace.c (ffffffff81aca388)
Location: include/asm-generic/bitops-instrumented.h:141
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
