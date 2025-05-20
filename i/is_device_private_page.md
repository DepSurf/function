# Function: <code>is_device_private_page</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff826a4749)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8108fffd)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810e5505)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8111b9e4)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff811c03a5)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811c66c8)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ccd78)
Location: include/linux/memremap.h:163
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
In mm/page-writeback.c (ffffffff811dd45a)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811de908)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811e04e6)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff811e23ad)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e794f)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811f0671)
Location: include/linux/memremap.h:163
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81205aef)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81210864)
Location: include/linux/memremap.h:163
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
```
```
In mm/mincore.c (ffffffff8121125a)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812125a1)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8121d24e)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81222326)
Location: include/linux/memremap.h:163
Inline: True
```
```
In mm/madvise.c (ffffffff812242d8)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81227d72)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8123579a)
Location: include/linux/memremap.h:163
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
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff8123811b)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/ksm.c (ffffffff8123d842)
Location: include/linux/memremap.h:163
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
In mm/memory_hotplug.c (ffffffff8198a0ac)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124c56c)
Location: include/linux/memremap.h:163
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
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
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
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81255b1f)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125efc6)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812661da)
Location: include/linux/memremap.h:163
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
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff81268e17)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8126b83e)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8126c75b)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cc35)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff8127218c)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127ad0c)
Location: include/linux/memremap.h:163
Inline: True
```
```
In fs/pipe.c (ffffffff8127cb17)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81280444)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812a075b)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812a9ebe)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812b2034)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b8e93)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812cadc8)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff812da888)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd986)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812e2490)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff812ec190)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8131f9e9)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81343013)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8135d501)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/commit.c (ffffffff8136830b)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813717a6)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81374126)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81377d58)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813882a9)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81392e1e)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81448760)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff81467f81)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81468805)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff81469a31)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8146b38d)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8146d847)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8146db28)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8146dd53)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8146e041)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8146efd6)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8146f358)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7cb3)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81610576)
Location: include/linux/memremap.h:163
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff81618097)
Location: include/linux/memremap.h:163
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff816ae586)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff816ffbed)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md.c (ffffffff817b2825)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff817baaec)
Location: include/linux/memremap.h:163
Inline: True
```
```
In net/core/sock.c (ffffffff8182d523)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818378a3)
Location: include/linux/memremap.h:163
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
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp.c (ffffffff818a6a05)
Location: include/linux/memremap.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818b1051)
Location: include/linux/memremap.h:163
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
In mm/rmap.c (ffffffff8123f470)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8127021f)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8127fe77)
Location: include/linux/mm.h:880
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/rmap.c (ffffffff81253b85)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812848d1)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812947d9)
Location: include/linux/mm.h:913
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/rmap.c (ffffffff81265de5)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8129d9c5)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b0a5e)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812c241f)
Location: include/linux/mm.h:983
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
In mm/rmap.c (ffffffff81274712)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812af5ed)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c24be)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812d434f)
Location: include/linux/mm.h:996
Inline: True
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
In mm/rmap.c (ffffffff812a5a52)
Location: include/linux/mm.h:1110
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812e567b)
Location: include/linux/mm.h:1110
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812f92e1)
Location: include/linux/mm.h:1110
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff8130aa25)
Location: include/linux/mm.h:1110
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
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
In mm/rmap.c (ffffffff812b0ec3)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f0a4b)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8130516e)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff81316905)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
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
In mm/rmap.c (ffffffff812b6053)
Location: include/linux/mm.h:1182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f6d9b)
Location: include/linux/mm.h:1182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff8130a60d)
Location: include/linux/mm.h:1182
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff8131cb55)
Location: include/linux/mm.h:1182
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
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
In mm/rmap.c (ffffffff812f9cc1)
Location: include/linux/mm.h:1186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
```
```
In mm/migrate.c (ffffffff813413fb)
Location: include/linux/mm.h:1186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff81355d6a)
Location: include/linux/mm.h:1186
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff81369ea5)
Location: include/linux/mm.h:1186
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
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
In mm/memory.c (ffffffff813402a4)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135f5ac)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81391b1e)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a0863)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b1a7c)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b8325)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c12)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813cea82)
Location: include/linux/memremap.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/memory.c (ffffffff813b8234)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813da40a)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8140eb7d)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8142006f)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81432523)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8143a035)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443dab)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453515)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/memory.c (ffffffff813ed014)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8140eb49)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81441f2e)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81454c7d)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81467c79)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146ecae)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814792f1)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81489209)
Location: include/linux/memremap.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/memory.c (ffffffff81418558)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8143b509)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/ksm.c (ffffffff8148ff5e)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81497960)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d70e)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a886c)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814b90e0)
Location: include/linux/memremap.h:160
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
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
In mm/rmap.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:996
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
In mm/rmap.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:996
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
In mm/rmap.c (c0000000003d9da0)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (c00000000043399c)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c0000000004510a0)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (c00000000046d9a0)
Location: include/linux/mm.h:996
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
In mm/rmap.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:996
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:996
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
In mm/rmap.c (ffffffff8126cd62)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a7bcd)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812baa9e)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812cc92f)
Location: include/linux/mm.h:996
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
In mm/rmap.c (ffffffff8125ed94)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8129958d)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812abc4a)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812bd79f)
Location: include/linux/mm.h:996
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
In mm/rmap.c (ffffffff8126ab02)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812a59dd)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812b88ae)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812ca73f)
Location: include/linux/mm.h:996
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
In mm/rmap.c (ffffffff8127a46b)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812b510d)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:expected_page_refs
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffff812c8eee)
Location: include/linux/mm.h:996
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memremap.c (ffffffff812db43f)
Location: include/linux/mm.h:996
Inline: True
```
</details>
</li>
</ul>

## Differences
