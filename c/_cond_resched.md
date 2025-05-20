# Function: <code>_cond_resched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81820610)
Location: kernel/sched/core.c:4615
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
  - kernel/cpu.c:get_online_cpus
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:get_signal
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_sigtimedwait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:flush_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:hib_wait_io
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:do_syslog
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:SYSC_init_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:zone_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_follow_link
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:bdi_unregister
  - mm/compaction.c:__reset_isolation_suitable
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:__do_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_prepare
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/vmalloc.c:vmap
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_fault
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:break_ksm
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:try_to_merge_with_ksm_page
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
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/memory_hotplug.c:get_online_mems
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/page_counter.c:page_counter_limit
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/zsmalloc.c:zs_compact
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - fs/file_table.c:__fput
  - fs/super.c:get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/inode.c:clear_inode
  - fs/inode.c:dispose_list
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:evict_inodes
  - fs/file.c:expand_files
  - fs/file.c:do_close_on_exec
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:write_inode_now
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:__generic_file_splice_read
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bdev_direct_access
  - fs/block_dev.c:blkdev_get
  - fs/notify/mark.c:fsnotify_mark_destroy
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/aio.c:aio_read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_clear_blocks
  - fs/dax.c:dax_clear_blocks
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:__break_lease
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/coredump.c:do_coredump
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpageflags_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/crypto.c:ext4_encrypt
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/shash.c:shash_compat_digest
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:blkdev_issue_discard
  - block/bsg.c:bsg_get_done_cmd
  - block/bsg.c:bsg_release
  - lib/idr.c:idr_preload
  - lib/idr.c:idr_alloc
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/pci/access.c:pci_vpd_pci22_wait
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:write_pool
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/firmware_class.c:firmware_data_read
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/power/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:lock_sock_nested
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:napi_disable
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:netdev_get_name
  - net/core/dev.c:register_netdevice
  - net/core/dst.c:dst_gc_task
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
```
**Symbols:**

```
ffffffff81820610-ffffffff81820633: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8189aa70)
Location: kernel/sched/core.c:4866
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:get_online_cpus
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:__ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_get_create
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:set_max_huge_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:get_online_mems
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_limit
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:lock_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - fs/file_table.c:__fput
  - fs/super.c:get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/inode.c:clear_inode
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bdev_direct_access
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:dax_fault
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_write_actor
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - lib/idr.c:idr_alloc
  - lib/idr.c:idr_preload
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_class.c:firmware_rw
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/power/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/dst.c:dst_gc_task
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff8189aa70-ffffffff8189aa93: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff818cf050)
Location: kernel/sched/core.c:4904
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:get_online_cpus
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_timed_futex_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_get_create
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:get_online_mems
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_limit
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:lock_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:dput
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/inode.c:clear_inode
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bdev_direct_access
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:grab_mapping_entry
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:update_backups
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/idr.c:idr_alloc
  - lib/idr.c:idr_preload
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xb_write
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:SyS_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_class.c:firmware_rw
  - drivers/base/regmap/regmap.c:regmap_async_complete
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:mddev_detach
  - drivers/md/md.c:md_super_wait
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/dst.c:dst_gc_task
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/netlink/genetlink.c:genl_unregister_family
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff818cf050-ffffffff818cf08a: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819065b0)
Location: kernel/sched/core.c:4805
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kmod.c:__request_module
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/bpf/verifier.c:do_check
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_shutdown
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_limit
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:lock_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/inode.c:clear_inode
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:dax_writeback_mapping_range
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/shash.c:shash_ahash_digest
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-zoned.c:blkdev_reset_zones
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:__gpiod_free
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_class.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dax/super.c:dax_direct_access
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/bitmap.c:bitmap_wait_behind_writes
  - drivers/md/bitmap.c:bitmap_wait_behind_writes
  - drivers/md/bitmap.c:bitmap_free
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff819065b0-ffffffff819065ea: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81990640)
Location: kernel/sched/core.c:4849
Inline: True
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/memremap.c:devm_memremap_pages
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_shutdown
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_limit
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:lock_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/hmm.c:hmm_vma_alloc_locked_page
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:d_invalidate
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_sb
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/inode.c:clear_inode
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:dax_writeback_mapping_range
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/shash.c:shash_ahash_digest
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_class.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dax/super.c:dax_direct_access
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81990640-ffffffff8199067e: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819eceb0)
Location: kernel/sched/core.c:4988
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/smp.c:on_each_cpu_cond
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:lock_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/hmm.c:hmm_vma_alloc_locked_page
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:dax_writeback_mapping_range
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/mls.c:mls_convert_context
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/shash.c:shash_ahash_digest
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_get_done_cmd
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rht_deferred_worker
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm-interface.c:tpm_getcap
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-interface.c:tpm_startup
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:skb_copy_and_csum_datagram
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff819eceb0-ffffffff819eced9: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a280e0)
Location: kernel/sched/core.c:4971
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/hmm.c:hmm_vma_alloc_locked_page
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:blkdev_get
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/crypto/crypto.c:fscrypt_encrypt_page
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:iomap_page_mkwrite
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_actor
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/shash.c:shash_ahash_digest
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rht_deferred_worker
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81a280e0-ffffffff81a28109: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a98870)
Location: kernel/sched/core.c:5424
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/ec.c:__acpi_ec_flush_event
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:tpm_send
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81a98870-ffffffff81a98899: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad01c0)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81ad01c0-ffffffff81ad01e9: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bc89b0)
Location: kernel/sched/core.c:5848
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:exit_mm
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:__wait_for_common
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:add_unformed_module
  - kernel/module.c:resolve_symbol_wait
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/uprobes.c:xol_take_insn_slot
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:discard_swap
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:hugetlb_page_mapping_lock_write
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/namei.c:pick_link
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_wq_submit_work
  - fs/io-wq.c:io_assign_current_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:coredump_wait
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:invalidate_dquots
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/readdir.c:fuse_readdir_cached
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/domain.c:find_attach
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rht_deferred_worker
  - lib/mpi/mpi-pow.c:mpi_powm
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_enter
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_autobind
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81bc89b0-ffffffff81bc89f7: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfee6)
Location: kernel/sched/core.c:6668
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:exit_mm
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:__wait_for_common
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:add_unformed_module
  - kernel/module.c:resolve_symbol_wait
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
  - kernel/events/uprobes.c:xol_take_insn_slot
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:remove_vma
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/ioremap.c:ioremap_page_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:discard_swap
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_interval_read_begin
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/file_table.c:__fput
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings_kernel
  - fs/pipe.c:pipe_wait_writable
  - fs/pipe.c:pipe_wait_readable
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:generic_pipe_buf_try_steal
  - fs/namei.c:pick_link
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/file.c:expand_files
  - fs/namespace.c:mnt_want_write
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:do_splice
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_try_steal
  - fs/remap_range.c:vfs_clone_file_range
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_wake
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:aio_write
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_write
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page_range
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/locks.c:locks_remove_file
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:do_coredump
  - fs/coredump.c:coredump_wait
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:add_dquot_ref
  - fs/quota/dquot.c:invalidate_dquots
  - fs/quota/quota.c:quotactl_block
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/kernfs/dir.c:kernfs_drain
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_update_super_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:journal_kill_thread
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/dax.c:alloc_dax_mapping_reclaim
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/ss/symtab.c:symtab_insert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/domain.c:find_attach
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_alloc_map_and_requests
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rht_deferred_worker
  - lib/mpi/mpi-pow.c:mpi_powm
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:virtio_device_restore
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_oom_notify
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_free_page_report
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_xs.c:xs_request_enter
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_bvec
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/dma-buf.c:dma_buf_map_attachment
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:open_wait
  - drivers/scsi/sg.c:open_wait
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/devio.c:proc_wait_for_resume
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:netdev_rx_handler_unregister
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:dev_remove_offload
  - net/core/dev.c:dev_remove_pack
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_autobind
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81c41780-ffffffff81c417c7: _cond_resched (STB_GLOBAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff810292a0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810661e9)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067d78)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069338)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f705)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff810abee2)
Location: include/linux/sched.h:1910
Inline: True
```
```
In kernel/ptrace.c (ffffffff810b1a8e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff810c61e8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff810cac7d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff810cd7d0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/fair.c (ffffffff810e976b)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff81c377e0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/rcu/update.c (ffffffff8112c8ed)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112fd32)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/futex.c (ffffffff8115974a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
```
```
In kernel/module.c (ffffffff811646ec)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
```
```
In kernel/kexec_core.c (ffffffff81167577)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff8117642f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff81183ebe)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/hung_task.c (ffffffff811a20b2)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff811ae090)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff811b61df)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/bpf/verifier.c (ffffffff8120f803)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121ad07)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8121d2de)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff812205b7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122587e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
```
In kernel/bpf/cpumap.c (ffffffff812342b1)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81240cd7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff8125d013)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8126ad39)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff812705fa)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81278e48)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff81280d1d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/vmstat.c (ffffffff81284462)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff8128654b)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
```
```
In mm/percpu.c (ffffffff8128b0d8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
```
```
In mm/compaction.c (ffffffff81292542)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff8129620f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff81298da8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812a648e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a6b05)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812a83fb)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mmap.c (ffffffff812abb7d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff812af3c9)
Location: include/linux/sched.h:1910
Inline: True
```
```
In mm/mremap.c (ffffffff812b0d85)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b4b75)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff812b88b9)
Location: include/linux/sched.h:1910
Inline: True
```
```
In mm/page_alloc.c (ffffffff81c2c7b5)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81c30e1f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81c2d7ca)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff812c9bcd)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff812ca3a2)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swap_state.c (ffffffff812cbc9e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff812d1d4c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff812d7acd)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff812e20a7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812e649a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812f85b5)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff813001a9)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff81306343)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In mm/page_counter.c (ffffffff81306946)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff8130ad30)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff81311893)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff8131204c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff813182b4)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
```
In mm/userfaultfd.c (ffffffff8131b307)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8131bb26)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memremap.c (ffffffff8131c4c3)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In mm/memfd.c (ffffffff8131e126)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff8132d88e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff81333807)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/ioctl.c (ffffffff8133cf2e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ioctl.c:__generic_block_fiemap
```
```
In fs/select.c (ffffffff8133fd5d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff813455d6)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff813494e1)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff8134b89a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff81359872)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8135f3d4)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff81364a49)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8136e572)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff8137a179)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380b72)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813834bb)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
```
```
In fs/userfaultfd.c (ffffffff8138861c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8139a3f8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:tctx_task_work
```
```
In fs/io-wq.c (ffffffff813a2db7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/dax.c (ffffffff813a658a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff813aec8e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff813b059a)
Location: include/linux/sched.h:1910
Inline: True
```
```
In fs/mbcache.c (ffffffff813bd166)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff813c0af9)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff813c4c1b)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/quota/dquot.c (ffffffff813cb4b3)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff813d1662)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff813d8cb8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff813dc8bd)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/page.c (ffffffff813e4c08)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff813f2b5d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff813f3a10)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813fcbf0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff8140789b)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inode.c (ffffffff8140ef67)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff81421dfe)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff8142b044)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff814505c2)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/jbd2/commit.c (ffffffff8146275f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463531)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff81464c6f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
```
```
In fs/hugetlbfs/inode.c (ffffffff814734d0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff814797b0)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff814aaf3f)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff814b1b25)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff814b91ef)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff814e3db7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff814e433a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff814e8654)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff814f0534)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff81538df8)
Location: include/linux/sched.h:1910
Inline: True
```
```
In crypto/skcipher.c (ffffffff81548c91)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81549800)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In block/blk-lib.c (ffffffff815717fe)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff8157870c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In block/blk-cgroup.c (ffffffff8158d6d2)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
```
```
In block/blk-zoned.c (ffffffff8159c10d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
```
```
In lib/rhashtable.c (ffffffff815b5dde)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/mpi/mpi-pow.c (ffffffff815e94b9)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163853c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/video/console/vgacon.c (ffffffff816680e5)
Location: include/linux/sched.h:1910
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81714d6d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/tty/tty_io.c (ffffffff81734f36)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753c35)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff8176d208)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff8176ef67)
Location: include/linux/sched.h:1910
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e29c4)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/spi/spi.c (ffffffff8186db7a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892724)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
```
In drivers/input/mousedev.c (ffffffff8191951d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff8191a5e4)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81920ecf)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81c18e9a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff8195fd36)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196c6bd)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/socket.c (ffffffff819c7e7c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff819cdcbb)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/dev.c (ffffffff819f2f91)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff819fc29c)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81a04550)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81a3729d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
```
In net/sched/sch_api.c (ffffffff81a5989b)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81a6aee5)
Location: include/linux/sched.h:1910
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a70c0e)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c3af)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99fd8)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8e6)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bc0d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/udp.c (ffffffff81accc20)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/fib_trie.c (ffffffff81aea32a)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/nexthop.c (ffffffff81af84e7)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
```
```
In net/unix/af_unix.c (ffffffff81b21f91)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/udp.c (ffffffff81b5463d)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81baf292)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbaff4)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbcc04)
Location: include/linux/sched.h:1910
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
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
In arch/x86/xen/mmu_pv.c (ffffffff8102d9fa)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810713d7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810721d8)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8107367b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0a6e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff810bd6e2)
Location: include/linux/sched.h:2027
Inline: True
```
```
In kernel/ptrace.c (ffffffff810c3b7e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff810d8ea3)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff810ddb7d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff810e09bb)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/core.c (ffffffff810f6c80)
Location: include/linux/sched.h:2027
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81100ffb)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff81d560a0)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/rcu/update.c (ffffffff8114d605)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81151782)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/futex.c (ffffffff8117e41a)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
```
In kernel/module.c (ffffffff81189e5c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
```
```
In kernel/kexec_core.c (ffffffff8118cd27)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff8119da6d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff811ac26e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/hung_task.c (ffffffff811cb867)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff811d7e60)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff811e03cf)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/bpf/syscall.c (ffffffff812315a5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
```
```
In kernel/bpf/verifier.c (ffffffff812441b7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff81251b07)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8125425d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff81257db7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d88e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
```
```
In kernel/bpf/cpumap.c (ffffffff8126dff9)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8127b6c7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff81298f2b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812a7af9)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff812ae285)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b6c27)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff812bf169)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/util.c (ffffffff812c109b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/util.c:copy_huge_page
```
```
In mm/vmstat.c (ffffffff812c2b44)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff812c58a8)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff812ca344)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/compaction.c (ffffffff812d1ebd)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff812d699f)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff812d9767)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812e794e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812e7fe5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff812e9a3b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mmap.c (ffffffff812ed264)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mprotect.c (ffffffff812f0bf8)
Location: include/linux/sched.h:2027
Inline: True
```
```
In mm/mremap.c (ffffffff812f27bf)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f69c5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff812ff484)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/page_alloc.c (ffffffff81d4aec5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81d4f742)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81d4c0a0)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff8130ebed)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff8130f3d0)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swap_state.c (ffffffff81310e0d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8131753c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff8131e3f2)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:update_and_free_pages_bulk
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81329187)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8132e36a)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81342c69)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81349df9)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff81350193)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_file
```
```
In mm/page_counter.c (ffffffff81350796)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff81353446)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff8135cc5b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff8135d8ba)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8135f39d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/zsmalloc.c (ffffffff813647bc)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
```
In mm/userfaultfd.c (ffffffff81368232)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff81368de6)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memremap.c (ffffffff813697c0)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In mm/memfd.c (ffffffff8136b4d8)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff8137b0ae)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff81381137)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/select.c (ffffffff8138d597)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff813931e6)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff81397231)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff813996da)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff813a7d12)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff813adfe4)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff813b2f09)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff813bd158)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff813c6e3a)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cdb32)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813d075b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
```
```
In fs/userfaultfd.c (ffffffff813d595d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81cc5e5c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sqd_handle_event
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:tctx_task_work
```
```
In fs/io-wq.c (ffffffff813f23a1)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/dax.c (ffffffff813f5ffa)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff813fe82e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff8140018a)
Location: include/linux/sched.h:2027
Inline: True
```
```
In fs/mbcache.c (ffffffff8140cf10)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff8141091e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff8141467c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
```
```
In fs/quota/dquot.c (ffffffff8141c41d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff81422b62)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff8142a3e8)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff8142df9d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/kcore.c (ffffffff81435388)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff814367d8)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff81444b46)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff81445ad3)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8144ef9d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff8145a13b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inline.c (ffffffff81460b7e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/inode.c (ffffffff81461cac)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff81474516)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff8147f04c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff814a38ab)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/orphan.c (ffffffff814b113d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/commit.c (ffffffff814b7c55)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b8ab4)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff814ba5bf)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca0c5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff814d0d3d)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff815033ff)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff8150a0d5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff81511a1f)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff8153d1d7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff8153d75a)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff81541f94)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff8154aa9e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff81597618)
Location: include/linux/sched.h:2027
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a9471)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815a9fe0)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In block/blk-exec.c (ffffffff815d37a2)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - block/blk-exec.c:blk_execute_rq
```
```
In block/blk-lib.c (ffffffff815d5f0e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff815dd820)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In block/blk-cgroup.c (ffffffff815f3152)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
```
In block/blk-zoned.c (ffffffff8160479b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In lib/rhashtable.c (ffffffff8161c27e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/mpi/mpi-pow.c (ffffffff81655862)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a886c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/proc.c (ffffffff816b9930)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/console/vgacon.c (ffffffff816db355)
Location: include/linux/sched.h:2027
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81791d4b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/tty_io.c (ffffffff817b5936)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf4bb)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d7181)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff817f2b98)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff817f4749)
Location: include/linux/sched.h:2027
Inline: True
```
```
In drivers/block/loop.c (ffffffff8186ff8c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/spi/spi.c (ffffffff818fdbde)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819264e5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
```
In drivers/input/mousedev.c (ffffffff819bb8dd)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff819bcb06)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff819c3c9f)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81d28499)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81a07ce6)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a14bcd)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In net/socket.c (ffffffff81a771cc)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff81a7d498)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/net_namespace.c (ffffffff81a8dd17)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_exit_list
```
```
In net/core/dev.c (ffffffff81aa3df5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81aae2e5)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81ab6b3c)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81aecdb7)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
```
```
In net/sched/sch_api.c (ffffffff81b1295b)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81b244e5)
Location: include/linux/sched.h:2027
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81b2a52e)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81b4737f)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b55448)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d56)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57310)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/udp.c (ffffffff81b8b5b6)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/fib_trie.c (ffffffff81bab440)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
```
```
In net/ipv4/nexthop.c (ffffffff81bb9687)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit
```
```
In net/unix/af_unix.c (ffffffff81be6f42)
Location: include/linux/sched.h:2027
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1bac4)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7cf92)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8aacf)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8ca64)
Location: include/linux/sched.h:2027
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
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
In arch/x86/xen/mmu_pv.c (ffffffff8103283c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107f337)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810805d0)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ad6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082308)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c69c1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff810d4845)
Location: include/linux/sched.h:2042
Inline: True
```
```
In kernel/ptrace.c (ffffffff810db2c3)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff810f26ad)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff810f7984)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff810fab45)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/core.c (ffffffff8110b29b)
Location: include/linux/sched.h:2042
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8111c727)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff81f28086)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
```
```
In kernel/rcu/update.c (ffffffff8117441d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/tree.c (ffffffff81179e8f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff8118fddc)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/module/main.c:__do_sys_init_module
```
```
In kernel/futex/core.c (ffffffff811b2f82)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff811b5839)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
```
In kernel/futex/requeue.c (ffffffff811b6102)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff811b715f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
```
```
In kernel/kallsyms.c (ffffffff811ba24b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
```
In kernel/kexec_core.c (ffffffff811bc3c6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff811cdcfc)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff811ddc8f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/hung_task.c (ffffffff811ff629)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff8120d591)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff81213fa6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/bpf/syscall.c (ffffffff812747eb)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
```
```
In kernel/bpf/verifier.c (ffffffff81289bc7)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129974e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8129d07d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff812a09e4)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff812b902d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_check_type_tags
```
```
In kernel/bpf/cpumap.c (ffffffff812bce54)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff812cf589)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff812ef7eb)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff812fd428)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff81307735)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81312b32)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8131ae20)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/util.c (ffffffff8131e011)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/vmstat.c (ffffffff8131fd41)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff813234b8)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff81326cd8)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/compaction.c (ffffffff81331c8e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff81335d2b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff8133977a)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81348b02)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813492e1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81349bbb)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff813505ef)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mmu_gather.c (ffffffff81352cde)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_batch_pages_flush
```
```
In mm/mprotect.c (ffffffff813544b4)
Location: include/linux/sched.h:2042
Inline: True
```
```
In mm/mremap.c (ffffffff813562fa)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135bb52)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff8136069b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
  - mm/vmalloc.c:vm_area_alloc_pages
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/page_alloc.c (ffffffff81f1a4d1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff81f1f665)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff81f1ba14)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff81376a72)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffffffff813796b2)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (ffffffff8138275e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff83490c5b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff813983ec)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8139e6e2)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b5198)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff813c06cd)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff813c8352)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/page_counter.c (ffffffff813c8ab6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff813cdf87)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff813d692b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7a7f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813d9a27)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/zsmalloc.c (ffffffff813e274e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In mm/userfaultfd.c (ffffffff813e5a5d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff813e6746)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memfd.c (ffffffff813e953e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff813fb612)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff81404ab5)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/select.c (ffffffff8140e9f4)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81414916)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff8141933f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff8141c054)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff8142a98e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff81435161)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff81437ffc)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff81443f7b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff8144e171)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455bd5)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81459724)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
```
```
In fs/userfaultfd.c (ffffffff8145fb56)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/dax.c (ffffffff81469bc6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff8147234b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81473fad)
Location: include/linux/sched.h:2042
Inline: True
```
```
In fs/mbcache.c (ffffffff81481d75)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff8148626a)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff81488b39)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/quota/dquot.c (ffffffff81491d7c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff81499c78)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff814a3947)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff814a7c2d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/kcore.c (ffffffff814af52c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff814b0f18)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff814c0ae9)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff814c1b02)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814ca57e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff814d7df9)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inode.c (ffffffff814e208e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff814f6559)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff81501fd3)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff8152ad4e)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/orphan.c (ffffffff81539bf1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/commit.c (ffffffff81541706)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81542682)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff8154441d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
```
In fs/hugetlbfs/inode.c (ffffffff81555de1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff8155d8dd)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff81594a80)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff8159be2b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff815a3e1d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff815d4c68)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff815d50c3)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff815d9d74)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff815e36b5)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff816394a4)
Location: include/linux/sched.h:2042
Inline: True
```
```
In crypto/skcipher.c (ffffffff816508c6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81651da6)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In block/blk-lib.c (ffffffff816824e7)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff8168b2de)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-cgroup.c (ffffffff816a46eb)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
  - block/blk-cgroup.c:blkg_destroy_all
```
```
In block/blk-zoned.c (ffffffff816b7f05)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In io_uring/io_uring.c (ffffffff81e92bdc)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sqd_handle_event
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_add_buffers
  - io_uring/io_uring.c:io_iopoll_try_reap_events
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/io-wq.c (ffffffff816dae5b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/rhashtable.c (ffffffff816eab41)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/mpi/mpi-pow.c (ffffffff8176ce0a)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cb4d3)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/proc.c (ffffffff817dde42)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/console/vgacon.c (ffffffff8180490d)
Location: include/linux/sched.h:2042
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff818ca757)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/tty_io.c (ffffffff818f1ac1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/tty_buffer.c (ffffffff818fb986)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff819152d1)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff819336e8)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81934329)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/block/loop.c (ffffffff819b7589)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/spi/spi.c (ffffffff81a4f23f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7b795)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
```
In drivers/input/mousedev.c (ffffffff81b1ae84)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff81b1cfed)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81b2472c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81ef4509)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81b70446)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d6a4)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/md/dm-stats.c (ffffffff81b7f01b)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:dm_stats_list
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In net/socket.c (ffffffff81bea4ec)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff81bf0afe)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/net_namespace.c (ffffffff81c038b7)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_exit_list
```
```
In net/core/dev.c (ffffffff81c17c2f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81c26fc5)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81c3092a)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81c6f9bc)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
```
In net/sched/sch_api.c (ffffffff81c9af15)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81cac6d6)
Location: include/linux/sched.h:2042
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb4151)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81cd44df)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce314f)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a79)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce528c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/udp.c (ffffffff81d1bf67)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81d4d5f2)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
```
```
In net/unix/af_unix.c (ffffffff81d7ffe0)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/udp.c (ffffffff81db8248)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/fib6_rules.c (ffffffff81de155d)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
```
```
In net/mptcp/protocol.c (ffffffff81e23015)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff81e3199c)
Location: include/linux/sched.h:2042
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
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
In arch/x86/xen/mmu_pv.c (ffffffff8103a24c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109124e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092f08)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810944f6)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094d58)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e395b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff810f375d)
Location: include/linux/sched.h:2069
Inline: True
```
```
In kernel/ptrace.c (ffffffff810fb523)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff81114051)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff8111a171)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff8111d9ad)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/core.c (ffffffff8113167b)
Location: include/linux/sched.h:2069
Inline: True
```
```
In kernel/sched/fair.c (ffffffff811442fa)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff820d3c56)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_flush_all
```
```
In kernel/rcu/update.c (ffffffff811ab40b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/tree.c (ffffffff811b0f5a)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811ccd6d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/module/main.c:__do_sys_init_module
```
```
In kernel/futex/core.c (ffffffff811f3e72)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff811f6959)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
```
In kernel/futex/requeue.c (ffffffff811f7232)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff811f82ef)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
```
```
In kernel/kallsyms.c (ffffffff811fbf32)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
```
In kernel/kexec_core.c (ffffffff811fe246)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff8121164c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff8122374f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/hung_task.c (ffffffff8124703e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff81257e88)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff8125d986)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/bpf/syscall.c (ffffffff812cba13)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
```
```
In kernel/bpf/verifier.c (ffffffff812e05e0)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f558d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff812f8f4e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff812fed04)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff8131b03d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_check_type_tags
```
```
In kernel/bpf/cpumap.c (ffffffff813202b8)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81337859)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff8135a54b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff81367d48)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff81371893)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81385f80)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8138ebeb)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/util.c (ffffffff81391a6f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/vmstat.c (ffffffff81393be0)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff81397d08)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/percpu.c (ffffffff8139b993)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/compaction.c (ffffffff813a8996)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff813acb2b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff813b107f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff813c0f7b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813c16a8)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c1f3d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff813c9f9d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mmu_gather.c (ffffffff813cce1e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_batch_pages_flush
```
```
In mm/mprotect.c (ffffffff813ce9dc)
Location: include/linux/sched.h:2069
Inline: True
```
```
In mm/mremap.c (ffffffff813d0928)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813d680d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff813e28f4)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/page_alloc.c (ffffffff820c2303)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:set_zone_contiguous
```
```
In mm/shuffle.c (ffffffff820c88bb)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff820c39a4)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff813f4352)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff813f712c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (ffffffff813fc6b8)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/hugetlb.c (ffffffff83ec3e01)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff814181a4)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8141def2)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8143535c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81443199)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff8144cc9a)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
```
```
In mm/page_counter.c (ffffffff8144d1d1)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff8145306a)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff8145c410)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d65f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8145fdce)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/zsmalloc.c (ffffffff81469c9c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In mm/userfaultfd.c (ffffffff8146d561)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e246)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memfd.c (ffffffff81471520)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814856b2)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff8148ef42)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/select.c (ffffffff8149958c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8149fdf6)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff814a4d5f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff814a818d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff814b9111)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814c31a1)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff814c647c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff814d28fc)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff814dc861)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4b65)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff814e8b84)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
```
```
In fs/userfaultfd.c (ffffffff814efc20)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/dax.c (ffffffff814fa316)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff81503e43)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815061fb)
Location: include/linux/sched.h:2069
Inline: True
```
```
In fs/mbcache.c (ffffffff81514afc)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff81519b2a)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff8151c809)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/quota/dquot.c (ffffffff815259dc)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff8152deda)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff81538c67)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff8153d15d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/kcore.c (ffffffff81545dfe)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81547888)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff81558bc9)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff81559db9)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81562c18)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff81570b59)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inode.c (ffffffff8157b3f7)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff81590908)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff8159cb7e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff815c9bce)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/orphan.c (ffffffff815d8121)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/commit.c (ffffffff815e034c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e13b4)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff815e342d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
```
In fs/hugetlbfs/inode.c (ffffffff815f74d9)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff815ff92d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff8163d730)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff8164522b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff8164dadd)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff81682e18)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff816832b7)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff81688849)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff8169291c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff816f0b14)
Location: include/linux/sched.h:2069
Inline: True
```
```
In crypto/skcipher.c (ffffffff8170a076)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8170b7d6)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In block/blk-lib.c (ffffffff8173fb87)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff817492de)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-cgroup.c (ffffffff817633f0)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-zoned.c (ffffffff81778515)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In io_uring/io_uring.c (ffffffff817926f3)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:handle_tw_list
```
```
In io_uring/sqpoll.c (ffffffff8179a729)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/tctx.c (ffffffff8179bfbd)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
```
In io_uring/kbuf.c (ffffffff8179ec44)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/kbuf.c:io_destroy_buffers
```
```
In io_uring/io-wq.c (ffffffff817a6f64)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/rhashtable.c (ffffffff817daddb)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/mpi/mpi-pow.c (ffffffff8189c4ea)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e96d3)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/proc.c (ffffffff81900972)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/console/vgacon.c (ffffffff8193317d)
Location: include/linux/sched.h:2069
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81a1b301)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/tty_io.c (ffffffff81a49b39)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54daf)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70568)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff81a92202)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81a93f59)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/block/loop.c (ffffffff81b2c889)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/spi/spi.c (ffffffff81bd6d3c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/input/mousedev.c (ffffffff81cacc14)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff81caef7d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81cb7bdc)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81cfa04d)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d0cd76)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:dm_wq_requeue_work
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1b5d4)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/md/dm-stats.c (ffffffff81d1e34b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:dm_stats_list
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In net/socket.c (ffffffff81d96d9c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff81d9d16e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/net_namespace.c (ffffffff81db2f07)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_exit_list
```
```
In net/core/dev.c (ffffffff81dd1adf)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81dd9ade)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81de3c5b)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81e2787c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
```
In net/sched/sch_api.c (ffffffff81e573a5)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81e6a2d6)
Location: include/linux/sched.h:2069
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81e723b1)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81e9479f)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea55f0)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea63c3)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea847c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/udp.c (ffffffff81ee2e4c)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f16ef2)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
```
```
In net/unix/af_unix.c (ffffffff81f4bd1e)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/udp.c (ffffffff81f88278)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb39ed)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
```
```
In net/mptcp/protocol.c (ffffffff81ff9d95)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff82009fe1)
Location: include/linux/sched.h:2069
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
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
In arch/x86/xen/mmu_pv.c (ffffffff8103a2c5)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff8105aa37)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109418c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095e58)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097487)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097c48)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810eefe2)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff810ffaad)
Location: include/linux/sched.h:2080
Inline: True
```
```
In kernel/ptrace.c (ffffffff81107348)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff811217f7)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff811273e1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff8112ab9d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/core.c (ffffffff8113f8cb)
Location: include/linux/sched.h:2080
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81154a7a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff82157ed6)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_flush_all
```
```
In kernel/rcu/update.c (ffffffff811bd32b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/tree.c (ffffffff811c22ed)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811e028d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/module/main.c:__do_sys_init_module
```
```
In kernel/futex/core.c (ffffffff81208602)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff8120b16f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
```
In kernel/futex/requeue.c (ffffffff8120ba17)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff8120ca9c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
```
```
In kernel/kallsyms.c (ffffffff81211742)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
```
In kernel/kexec_core.c (ffffffff81213506)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff81227030)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff81239ddd)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/auditsc.c (ffffffff812450d9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
```
```
In kernel/hung_task.c (ffffffff8125e0ce)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff8126f477)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff81274bff)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace_osnoise.c (ffffffff81295d66)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
```
In kernel/bpf/syscall.c (ffffffff812f335e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
```
```
In kernel/bpf/verifier.c (ffffffff8130a769)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff8132332d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff813279b0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff8132d8f1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff8134a62d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_check_type_tags
```
```
In kernel/bpf/cpumap.c (ffffffff8134ff05)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81368629)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff8138be5f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff8139a399)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff813a39a0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813b924d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813c1fbe)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/util.c (ffffffff813c445e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/vmstat.c (ffffffff813c65eb)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff813cac88)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff813cc0d5)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mm_init.c:set_zone_contiguous
  - mm/mm_init.c:memmap_init_range
```
```
In mm/percpu.c (ffffffff813ce973)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/compaction.c (ffffffff813dbb6a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff813e0ebe)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff813e5474)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff813f5d10)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff813f6651)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f7603)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff813fe4dc)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mmu_gather.c (ffffffff8140177e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_batch_pages_flush
```
```
In mm/mprotect.c (ffffffff814032ef)
Location: include/linux/sched.h:2080
Inline: True
```
```
In mm/mremap.c (ffffffff81405349)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140b764)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff814174c3)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/page_alloc.c (ffffffff81420836)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/shuffle.c (ffffffff8214cb3b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff82147785)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff81427994)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff8142a405)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (ffffffff8142f9be)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff81437bba)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff836e8eb2)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:return_unused_surplus_pages
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff8144b714)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81452b77)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8146a6da)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/huge_memory.c (ffffffff814780b9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff814825bf)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
```
```
In mm/page_counter.c (ffffffff81482a91)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff81488cc0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff814920b0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff81492d8d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814955c0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/zsmalloc.c (ffffffff8149ed5b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In mm/userfaultfd.c (ffffffff814a1fa6)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814a2c06)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memfd.c (ffffffff814a5a74)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ba712)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff814c4732)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/select.c (ffffffff814ce669)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff814d5116)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff814d9eef)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff814dd16d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff814ecc51)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff814f8581)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff814fbe8c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8150920a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff815130b1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bbb5)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8151f8e7)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_clear_and_put
```
```
In fs/userfaultfd.c (ffffffff81526947)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/dax.c (ffffffff8152f92b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff8153b8c3)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8153d52d)
Location: include/linux/sched.h:2080
Inline: True
```
```
In fs/mbcache.c (ffffffff8154c50b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff8155141a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff81554a09)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/quota/dquot.c (ffffffff8155de6f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff81566240)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff81570eaa)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff81575430)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/kcore.c (ffffffff8157d9cc)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff8157f4a8)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff81590a19)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff81591bee)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8159a94d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff815a8929)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inode.c (ffffffff815b5d6a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff815c7ac5)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff815d33c6)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff81601a8e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/orphan.c (ffffffff8160fcb1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/commit.c (ffffffff81617bf8)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618cad)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff8161abed)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f562)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff8163790d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff81675c30)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff8167d72f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff81686292)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff816baf98)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff816bb4b9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff816c1fac)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff816cae87)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff8172afb4)
Location: include/linux/sched.h:2080
Inline: True
```
```
In crypto/skcipher.c (ffffffff817435d9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81745652)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In block/blk-lib.c (ffffffff8177c0b1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff81785a1e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-cgroup.c (ffffffff817a2543)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-zoned.c (ffffffff817b7de8)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In io_uring/io_uring.c (ffffffff817d333e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff817db7a9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/tctx.c (ffffffff817dd0ed)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
```
In io_uring/kbuf.c (ffffffff817dfe34)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In io_uring/io-wq.c (ffffffff817e8097)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/rhashtable.c (ffffffff8181a054)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/mpi/mpi-pow.c (ffffffff818dea75)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192cce3)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/proc.c (ffffffff81943f1a)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/console/vgacon.c (ffffffff819775f0)
Location: include/linux/sched.h:2080
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81a644b1)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/tty_io.c (ffffffff81a941c9)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_tty_write
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f27f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abad28)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff81addaaa)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81adea89)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/virtio_console.c (ffffffff81ae260c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
```
```
In drivers/block/loop.c (ffffffff81b7cbc8)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/spi/spi.c (ffffffff81c2d76c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/virtio_net.c (ffffffff81c540b4)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
```
```
In drivers/input/mousedev.c (ffffffff81d1423b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff81d1656d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f29e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81d6977e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81d75b36)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:dm_wq_requeue_work
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84744)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/md/dm-stats.c (ffffffff81d87532)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:dm_stats_list
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In net/socket.c (ffffffff81e0540c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff81e0b9be)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/net_namespace.c (ffffffff81e234d7)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_exit_list
```
```
In net/core/dev.c (ffffffff81e426bf)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81e4a82e)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81e5513b)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81e9ce8c)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
```
In net/sched/sch_api.c (ffffffff81eb33d0)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81ec6296)
Location: include/linux/sched.h:2080
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81ece521)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81ef2f6f)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03d77)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04ba3)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06cfc)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/udp.c (ffffffff81f426e4)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f76bd2)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
```
```
In net/unix/af_unix.c (ffffffff81fabace)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/udp.c (ffffffff81fe8b92)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/fib6_rules.c (ffffffff8201418d)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
```
```
In net/mptcp/protocol.c (ffffffff820764ec)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff82086cd7)
Location: include/linux/sched.h:2080
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
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
In arch/x86/xen/mmu_pv.c (ffffffff81040785)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff81061cf7)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b66c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d398)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e9f7)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f1b8)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f82a2)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/softirq.c (ffffffff8110924d)
Location: include/linux/sched.h:1982
Inline: True
```
```
In kernel/ptrace.c (ffffffff81110c98)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/workqueue.c (ffffffff81129c74)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
```
```
In kernel/task_work.c (ffffffff811319c1)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (ffffffff811352bd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/sched/core.c (ffffffff8114a82b)
Location: include/linux/sched.h:1982
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81169982)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/printk/printk.c (ffffffff8223ad46)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_flush_all
```
```
In kernel/rcu/update.c (ffffffff811cd977)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/tree.c (ffffffff811de73d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_nocb_gp_kthread
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811f5fbd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/module/main.c:__do_sys_init_module
```
```
In kernel/futex/core.c (ffffffff8121f492)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:handle_futex_death
```
```
In kernel/futex/pi.c (ffffffff812226f3)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
```
In kernel/futex/requeue.c (ffffffff81222fa3)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff81223e6e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
```
```
In kernel/kallsyms.c (ffffffff81228dc2)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
```
In kernel/kexec_core.c (ffffffff8122b436)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_crash_segment
  - kernel/kexec_core.c:kimage_load_normal_segment
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
```
```
In kernel/cgroup/rstat.c (ffffffff8123edae)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/stop_machine.c (ffffffff81253aad)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/auditsc.c (ffffffff8125f02f)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
```
```
In kernel/hung_task.c (ffffffff8127800e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/trace/ftrace.c (ffffffff81289a87)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_replace_code
```
```
In kernel/trace/ring_buffer.c (ffffffff81291eca)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b13d6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
```
In kernel/trace/trace_events.c (ffffffff812c39dc)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/bpf/syscall.c (ffffffff813121ee)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
```
```
In kernel/bpf/verifier.c (ffffffff8132d2dd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/bpf_iter.c (ffffffff8134725d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8134c05d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/hashtab.c:htab_free_elems
```
```
In kernel/bpf/arraymap.c (ffffffff81351c91)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/btf.c (ffffffff81370ddd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_check_type_tags
```
```
In kernel/bpf/cpumap.c (ffffffff8137733e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81391549)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In mm/filemap.c (ffffffff813b59d0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/page-writeback.c (ffffffff813c4044)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/truncate.c (ffffffff813cd644)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff813e224d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_lruvec
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:walk_mm
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/shrinker.c (ffffffff813e4e33)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813ecd33)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
```
```
In mm/util.c (ffffffff813ee29b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/vmstat.c (ffffffff813f0ff7)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/backing-dev.c (ffffffff813f5c68)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/mm_init.c (ffffffff813f6a45)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mm_init.c:set_zone_contiguous
  - mm/mm_init.c:memmap_init_range
```
```
In mm/percpu.c (ffffffff813f94d3)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
```
```
In mm/compaction.c (ffffffff81405aca)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/workingset.c (ffffffff8140b78e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff8140fc6d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff814219ed)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:copy_user_large_folio
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81422301)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff81422a82)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mmap.c (ffffffff8142a91c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/mmu_gather.c (ffffffff8142deae)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_batch_pages_flush
```
```
In mm/mprotect.c (ffffffff8142f87f)
Location: include/linux/sched.h:1982
Inline: True
```
```
In mm/mremap.c (ffffffff8143185e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81438045)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/vmalloc.c (ffffffff81443fd3)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/page_alloc.c (ffffffff8144d5f6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/shuffle.c (ffffffff8222f64b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/shuffle.c:__shuffle_zone
```
```
In mm/memory_hotplug.c (ffffffff82229fc2)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/madvise.c (ffffffff814611aa)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffff81463ac5)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/page_io.c:generic_swapfile_activate
```
```
In mm/swapfile.c (ffffffff81469551)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8146f700)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff8147553f)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:update_and_free_pages_bulk
  - mm/hugetlb.c:bulk_vmemmap_restore_error
  - mm/hugetlb.c:bulk_vmemmap_restore_error
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81485121)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8148d377)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff814996bd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/huge_memory.c (ffffffff814a7806)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/khugepaged.c (ffffffff814b194b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:khugepaged
```
```
In mm/page_counter.c (ffffffff814b1e11)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff814b8340)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/swap_cgroup.c (ffffffff814c1ac0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/hugetlb_cgroup.c (ffffffff814c2485)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff814c4da0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/zsmalloc.c (ffffffff814ce4cb)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
```
```
In mm/userfaultfd.c (ffffffff814d341d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/page_idle.c (ffffffff814d3a96)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
```
```
In mm/memfd.c (ffffffff814d6a24)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/exec.c (ffffffff814ecc92)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/exec.c:copy_strings_kernel
```
```
In fs/namei.c (ffffffff814f6f12)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/select.c (ffffffff81500fa9)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff81507518)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:__dentry_kill
```
```
In fs/inode.c (ffffffff8150c66f)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/file.c (ffffffff8150faad)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/file.c:do_close_on_exec
  - fs/file.c:__close_range
  - fs/file.c:__close_range
```
```
In fs/libfs.c (ffffffff81520bc6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (ffffffff8152cd01)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff81530c6c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/splice.c:__splice_from_pipe
```
```
In fs/buffer.c (ffffffff8153de3c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/buffer.c:clean_bdev_aliases
```
```
In fs/notify/fsnotify.c (ffffffff81547561)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff815501b5)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81553ef7)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_clear_and_put
```
```
In fs/userfaultfd.c (ffffffff8155af10)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/dax.c (ffffffff8156480b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
```
```
In fs/verity/enable.c (ffffffff81570ba0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/read_metadata.c (ffffffff8157298d)
Location: include/linux/sched.h:1982
Inline: True
```
```
In fs/mbcache.c (ffffffff8158233b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/drop_caches.c (ffffffff8158731a)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/iomap/buffered-io.c (ffffffff8158abf9)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_file_unshare
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/quota/dquot.c (ffffffff81594550)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_load_quota_sb
```
```
In fs/proc/task_mmu.c (ffffffff8159e25a)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff815a984a)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readdir
```
```
In fs/proc/fd.c (ffffffff815add8b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
```
```
In fs/proc/kcore.c (ffffffff815b6412)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff815b7ee8)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/block_validity.c (ffffffff815c976a)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff815ca95e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815d378d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/ialloc.c (ffffffff815e16d9)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
```
In fs/ext4/inode.c (ffffffff815eeb15)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
```
In fs/ext4/mballoc.c (ffffffff815ff711)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/namei.c (ffffffff8160bb76)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff8163a82e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/ext4/orphan.c (ffffffff81648a71)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/jbd2/commit.c (ffffffff81650aea)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651c2e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff81653b0d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
```
```
In fs/hugetlbfs/inode.c (ffffffff81668a6f)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In fs/fat/fatent.c (ffffffff81670dfd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In ipc/msgutil.c (ffffffff816b1ff0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
  - ipc/msgutil.c:alloc_msg
```
```
In ipc/sem.c (ffffffff816b9aff)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In security/keys/gc.c (ffffffff816c26c3)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/selinux/ss/symtab.c (ffffffff816f7998)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - security/selinux/ss/symtab.c:symtab_insert
```
```
In security/selinux/ss/sidtab.c (ffffffff816f7eb9)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
```
In security/selinux/ss/policydb.c (ffffffff816fea6f)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
```
```
In security/selinux/ss/services.c (ffffffff81707ac6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_get_user_sids
```
```
In security/landlock/fs.c (ffffffff8176cad4)
Location: include/linux/sched.h:1982
Inline: True
```
```
In crypto/skcipher.c (ffffffff81785909)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81787891)
Location: include/linux/sched.h:1982
Inline: True
```
```
In block/blk-lib.c (ffffffff817be4a1)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In block/blk-mq.c (ffffffff817c7b66)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-cgroup.c (ffffffff817e6080)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
```
In block/blk-zoned.c (ffffffff817fcd27)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_zone_mgmt
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
```
```
In io_uring/io_uring.c (ffffffff8181714e)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:tctx_task_work
```
```
In io_uring/sqpoll.c (ffffffff8181fb00)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sqd_handle_event
```
```
In io_uring/tctx.c (ffffffff8182143d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_clean_tctx
```
```
In io_uring/kbuf.c (ffffffff818250c6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
```
```
In io_uring/io-wq.c (ffffffff8182de4c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In lib/rhashtable.c (ffffffff8185f3a4)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/crypto/mpi/mpi-pow.c (ffffffff8187567d)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - lib/crypto/mpi/mpi-pow.c:mpi_powm
```
```
In drivers/pci/pci-sysfs.c (ffffffff81975573)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_config
```
```
In drivers/pci/proc.c (ffffffff8198d1ea)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/console/vgacon.c (ffffffff819c1690)
Location: include/linux/sched.h:1982
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81ab6d11)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/tty_io.c (ffffffff81ae6c34)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_write
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1de1)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:flush_to_ldisc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0da98)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
```
```
In drivers/char/mem.c (ffffffff81b30e9a)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81b31ea9)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:get_random_bytes_user
```
```
In drivers/char/virtio_console.c (ffffffff81b359fc)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:remove_vqs
```
```
In drivers/block/loop.c (ffffffff81bd0af6)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c2e4)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
```
```
In drivers/spi/spi.c (ffffffff81ce015c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/virtio_net.c (ffffffff81d0a8c4)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:remove_vq_common
```
```
In drivers/input/mousedev.c (ffffffff81dc9e5b)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffff81dcc1ed)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4fce)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/md/md.c (ffffffff81e20314)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff81e2cc36)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:__set_swap_bios_limit
  - drivers/md/dm.c:dm_wq_requeue_work
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3bf04)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/md/dm-stats.c (ffffffff81e3ec42)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_print
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:dm_stats_list
  - drivers/md/dm-stats.c:dm_stats_cleanup
```
```
In net/socket.c (ffffffff81ec1ccc)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
```
```
In net/core/sock.c (ffffffff81ec83ae)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
```
```
In net/core/net_namespace.c (ffffffff81ee1437)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_exit_list
```
```
In net/core/dev.c (ffffffff81f012ef)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
```
```
In net/core/neighbour.c (ffffffff81f09550)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/rtnetlink.c (ffffffff81f144b4)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/netclassid_cgroup.c (ffffffff81f5f5c4)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
```
```
In net/sched/sch_api.c (ffffffff81f75ee0)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netlink/af_netlink.c (ffffffff81f89506)
Location: include/linux/sched.h:1982
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81f91d51)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/inetpeer.c (ffffffff81fb6eff)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7ffc)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8eac)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb01c)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2c29)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffb704)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
```
```
In net/ipv4/udp.c (ffffffff820086dc)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/nexthop.c (ffffffff8203d3a2)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
```
```
In net/unix/af_unix.c (ffffffff82078eed)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/udp.c (ffffffff820b66d1)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/fib6_rules.c (ffffffff820e32dd)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
```
```
In net/mptcp/protocol.c (ffffffff8214ae85)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c487)
Location: include/linux/sched.h:1982
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da1f28)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/arm64/kernel/sys_compat.c:compat_arm_syscall
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/mm/fault.c:do_page_fault
  - virt/kvm/kvm_main.c:__kvm_map_gfn
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:__wait_for_common
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:copy_chunked_from_user
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:copy_page_from_iter
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__arm64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/firmware/arm_sdei.c:sdei_unregister_ghes
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff800010da1f28-ffff800010da1f64: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e9a050)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/mm/fault.c:do_page_fault
  - arch/arm/mm/highmem.c:kmap
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_up
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__se_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_unlock_should_abort
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_unmap_ram
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:do_io_getevents
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify_sig_chain
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_unmap
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_map
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/tty/serial/imx.c:imx_uart_dma_exit
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/mtd/nand/raw/omap2.c:omap_wait
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_trx_complete
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_wait_for_idle
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_close_release_chan
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_close
  - sound/core/compress_offload.c:snd_compress_wait_for_drain
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_autobind
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c0e9a050-c0e9a0a0: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee32e0)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
  - arch/powerpc/kernel/rtas.c:rtas_busy_delay
  - arch/powerpc/kernel/rtasd.c:rtas_log_read
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/mem.c:flush_icache_user_range
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_bolt_mapping
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response_interruptible
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_wait_response
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/lpar.c:free_dtl_buffers
  - arch/powerpc/platforms/pseries/lpar.c:alloc_dtl_buffers
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:vfree
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wb_wait_for_completion
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/ext4_jbd2.c:ext4_journal_check_start
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir_cached
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:poke_blanked_console
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/hvc/hvsi.c:wait_for_state
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_send
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_recv
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_detach_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_attach_clk
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_free_context
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:md_bitmap_wait_writes
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/cpufreq/cpufreq.c:cpufreq_freq_transition_begin
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_autobind
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c000000000ee32e0-c000000000ee3354: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c5658)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/kmod.c:__request_module
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:vm_unmap_ram
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_set_nowrite
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:copy_page_from_iter
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__se_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:devm_power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_autobind
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffe0008c5658-ffffffe0008c56a0: _cond_resched (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6f030)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81a6f030-ffffffff81a6f059: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b3f0)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_nocb_gp_kthread
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/nvdimm/btt.c:btt_meta_init
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_dev_remove
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/core.c:nvme_wait_reset
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81a2b3f0-ffffffff81a2b419: _cond_resched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _cond_resched();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb440)
Location: kernel/sched/core.c:5615
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_punit_acquire
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_attach
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/task_work.c:task_work_run
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/smpboot.c:cpu_wait_death
  - kernel/kmod.c:__request_module
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:hib_wait_io
  - kernel/printk/printk.c:console_conditional_schedule
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_lock
  - kernel/printk/printk.c:devkmsg_read
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:synchronize_irq
  - kernel/irq/chip.c:handle_nested_irq
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:__wait_rcu_gp
  - kernel/rcu/sync.c:rcu_sync_enter
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_key
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_hold
  - kernel/cgroup/rstat.c:cgroup_rstat_flush
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_read_lock
  - kernel/stop_machine.c:stop_one_cpu
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/hung_task.c:watchdog
  - kernel/trace/ftrace.c:ftrace_replace_code
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/page-writeback.c:set_page_dirty_lock
  - mm/page-writeback.c:do_writepages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wb_get_create
  - mm/percpu.c:pcpu_balance_workfn
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:__reset_isolation_suitable
  - mm/workingset.c:shadow_lru_isolate
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:do_page_mkwrite
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/mincore.c:mincore_pte_range
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:remove_vma
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:__anon_vma_prepare
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:remove_vm_area
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/shuffle.c:__shuffle_zone
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/page_io.c:generic_swapfile_activate
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/dmapool.c:dma_pool_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:wait_while_offlining
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_ksm
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:putback_movable_pages
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/page_counter.c:page_counter_set_max
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/swap_cgroup.c:swap_cgroup_swapoff
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:async_free_zspage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/memremap.c:memunmap_pages
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/file_table.c:__fput
  - fs/super.c:__get_super_thawed
  - fs/exec.c:de_thread
  - fs/pipe.c:generic_pipe_buf_steal
  - fs/namei.c:trailing_symlink
  - fs/ioctl.c:__generic_block_fiemap
  - fs/select.c:do_select
  - fs/dcache.c:shrink_dcache_parent
  - fs/dcache.c:dput
  - fs/dcache.c:__dentry_kill
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:inode_insert5
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
  - fs/inode.c:dispose_list
  - fs/file.c:do_close_on_exec
  - fs/file.c:expand_files
  - fs/libfs.c:scan_positives
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/splice.c:write_pipe_buf
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:page_cache_pipe_buf_confirm
  - fs/splice.c:page_cache_pipe_buf_steal
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_page_mkwrite
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/block_dev.c:bd_start_claiming
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/aio.c:read_events
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_layout_busy_page
  - fs/verity/enable.c:build_merkle_tree
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/mbcache.c:mb_cache_shrink
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_actor
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/file.c:ext4_unwritten_wait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/transaction.c:add_transaction_credits
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/checkpoint.c:jbd2_journal_destroy_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/revoke.c:jbd2_journal_revoke
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_log_wait_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/squashfs/cache.c:squashfs_cache_get
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_mirror_bhs
  - fs/fat/misc.c:fat_sync_bhs
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment
  - fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment
  - fs/ecryptfs/crypto.c:ecryptfs_decrypt_page
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/fuse/dev.c:fuse_wait_aborted
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_page_mkwrite
  - fs/fuse/readdir.c:fuse_readdir
  - ipc/msgutil.c:free_msg
  - ipc/msgutil.c:load_msg
  - ipc/sem.c:exit_sem
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:wait_for_key_construction
  - security/selinux/hooks.c:__inode_security_revalidate
  - security/selinux/ss/hashtab.c:hashtab_insert
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:policydb_destroy
  - security/selinux/ss/policydb.c:range_tr_destroy
  - security/selinux/ss/policydb.c:filenametr_destroy
  - security/selinux/ss/services.c:security_get_user_sids
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:ns_revision_read
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/ahash.c:crypto_hash_walk_done
  - crypto/ahash.c:hash_walk_next
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-ioc.c:get_task_io_context
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_zero_pages
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:__blkdev_issue_write_zeroes
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - block/blk-mq.c:blk_mq_freeze_queue_wait
  - block/blk-zoned.c:blkdev_reset_zones
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/mpi/mpi-pow.c:mpi_powm
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/pci/access.c:pci_cfg_access_lock
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/acpi/osl.c:acpi_os_map_iomem
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_release
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
  - drivers/virtio/virtio.c:virtio_add_status
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xs_suspend
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/vt/vt_ioctl.c:vt_waitactive
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/hvc/hvc_console.c:hvc_write
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/firmware_loader/fallback.c:firmware_rw
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:transfer_xor
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle
  - drivers/nvdimm/bus.c:nd_bus_remove
  - drivers/nvdimm/claim.c:nsio_rw_bytes
  - drivers/dma-buf/dma-buf.c:dma_buf_unmap_attachment
  - drivers/dma-buf/udmabuf.c:kmap_udmabuf
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/usb/core/hcd.c:usb_hcd_disable_endpoint
  - drivers/usb/core/hcd.c:usb_hcd_flush_endpoint
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_request_reserve_slot
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/power/supply/power_supply_core.c:power_supply_put
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_super_wait
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_wait_behind_writes
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/dm.c:dm_wait_event
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:run_complete_job
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/sock.c:sock_no_sendpage
  - net/core/sock.c:__release_sock
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/datagram.c:__skb_datagram_iter
  - net/core/dev.c:synchronize_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netif_napi_del
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:__dev_close_many
  - net/core/dev.c:netdev_get_name
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/rtnetlink.c:__rtnl_unlock
  - net/core/netpoll.c:netpoll_poll_disable
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:update_classid_task
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/sched/sch_api.c:tc_fill_tclass
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/netlink/genetlink.c:genl_unregister_family
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/garbage.c:wait_for_unix_gc
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/rfkill/core.c:rfkill_fop_read
  - lib/ioremap.c:ioremap_page_range
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
**Symbols:**

```
ffffffff81adb440-ffffffff81adb469: _cond_resched (STB_GLOBAL)
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
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/task_work.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/hung_task.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/shuffle.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/page_counter.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ioctl.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/notify/fsnotify.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/quota/dquot.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In security/keys/gc.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In lib/mpi/mpi-pow.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/video/console/vgacon.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/socket.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/inetpeer.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/sched.h:1766
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
