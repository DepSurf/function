# Function: <code>put_devmap_managed_page</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff826cd756)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff81093abe)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810ed9a4)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81128505)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/sockmap.c (ffffffff811ceabd)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In kernel/bpf/stackmap.c (ffffffff811d0d7f)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811e06ae)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811e6b9e)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811e947c)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ede30)
Location: include/linux/mm.h:862
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
In mm/page-writeback.c (ffffffff811fe574)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811ffe93)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812021e9)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81203a8c)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120a9b6)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff81211dbe)
Location: include/linux/mm.h:862
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
In mm/gup.c (ffffffff81226c04)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812311bd)
Location: include/linux/mm.h:862
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
```
```
In mm/mincore.c (ffffffff81231d5a)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81233009)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8123f11c)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812440de)
Location: include/linux/mm.h:862
Inline: True
```
```
In mm/madvise.c (ffffffff81244eb6)
Location: include/linux/mm.h:862
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
In mm/swap_state.c (ffffffff812486ba)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124d610)
Location: include/linux/mm.h:862
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
In mm/zswap.c (ffffffff812503f7)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812586c6)
Location: include/linux/mm.h:862
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
```
```
In mm/mempolicy.c (ffffffff8125b356)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81260e0e)
Location: include/linux/mm.h:862
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
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff819e63d0)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8126fef2)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
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
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81279935)
Location: include/linux/mm.h:862
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127db74)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8128318a)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8128a4fe)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff8128dcf1)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff81290229)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812912c5)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812917c0)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff81297eee)
Location: include/linux/mm.h:862
Inline: True
```
```
In fs/exec.c (ffffffff812a1a71)
Location: include/linux/mm.h:862
Inline: True
```
```
In fs/pipe.c (ffffffff812a3a8a)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812a6597)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812c6c91)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812d0327)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812d9f53)
Location: include/linux/mm.h:862
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
In fs/block_dev.c (ffffffff812dc9f2)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812e0dbf)
Location: include/linux/mm.h:862
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
In fs/mpage.c (ffffffff812e37bc)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812f3ca6)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff813064ac)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309e51)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8130e960)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff8131999e)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8134dab1)
Location: include/linux/mm.h:862
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
In fs/ext4/inode.c (ffffffff8135a682)
Location: include/linux/mm.h:862
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
In fs/ext4/mballoc.c (ffffffff8135f9e2)
Location: include/linux/mm.h:862
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
In fs/ext4/move_extent.c (ffffffff813687f2)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81370f9c)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8138be36)
Location: include/linux/mm.h:862
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81396b0e)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8139ff6b)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813a2a2a)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813a655e)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6aa8)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813b7081)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c2c54)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813cbf14)
Location: include/linux/mm.h:862
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
In security/tomoyo/domain.c (ffffffff81428b11)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8147b9bb)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff81499551)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8149bd67)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c836)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149ccc5)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8149d831)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149eb36)
Location: include/linux/mm.h:862
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
In block/partitions/msdos.c (ffffffff814a0d96)
Location: include/linux/mm.h:862
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
In block/partitions/osf.c (ffffffff814a1513)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a16f4)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a19f4)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1c7f)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a1f36)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814a3094)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a330c)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f01d9)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff815f25af)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81649fd7)
Location: include/linux/mm.h:862
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8165196a)
Location: include/linux/mm.h:862
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff816ea950)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8173d187)
Location: include/linux/mm.h:862
Inline: True
```
```
In drivers/md/md.c (ffffffff817f5d27)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81802b2c)
Location: include/linux/mm.h:862
Inline: True
```
```
In net/core/sock.c (ffffffff81875e2b)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81881cc4)
Location: include/linux/mm.h:862
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
In net/core/dev.c (ffffffff8188dac6)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b3ad9)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818baa7d)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818bda3a)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/ipv4/tcp.c (ffffffff818fbab3)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81906697)
Location: include/linux/mm.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/xdp/xdp_umem.c (ffffffff819ccabb)
Location: include/linux/mm.h:862
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
In init/do_mounts.c (ffffffff82883734)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8109bd79)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810f9014)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81133de7)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811e08bd)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f0b02)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811f76fa)
Location: include/linux/mm.h:895
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
In kernel/memremap.c (ffffffff811fa13e)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ff42f)
Location: include/linux/mm.h:895
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
In mm/page-writeback.c (ffffffff81211204)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81212763)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81214b6b)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8121637f)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121d6b9)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff81223c5b)
Location: include/linux/mm.h:895
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
In mm/gup.c (ffffffff81239d03)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:get_user_pages_longterm
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124498d)
Location: include/linux/mm.h:895
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
```
```
In mm/mincore.c (ffffffff8124552a)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812467de)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81253738)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812587de)
Location: include/linux/mm.h:895
Inline: True
```
```
In mm/madvise.c (ffffffff81259509)
Location: include/linux/mm.h:895
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
In mm/swap_state.c (ffffffff8125cc90)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81261a27)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
```
```
In mm/zswap.c (ffffffff812648e7)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126cd98)
Location: include/linux/mm.h:895
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
```
```
In mm/mempolicy.c (ffffffff8126fe07)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812755e5)
Location: include/linux/mm.h:895
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
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a21be1)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812845a5)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
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
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128df52)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
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
In mm/khugepaged.c (ffffffff81291657)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812991dc)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129f467)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812a3631)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812a4c2e)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812a62e5)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a67e0)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff812ad208)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b6831)
Location: include/linux/mm.h:895
Inline: True
```
```
In fs/pipe.c (ffffffff812b8bda)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812bb667)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812dbe61)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812e6677)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812ef441)
Location: include/linux/mm.h:895
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
In fs/block_dev.c (ffffffff812f0c42)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f5b68)
Location: include/linux/mm.h:895
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
In fs/mpage.c (ffffffff812f8463)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81309354)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff8131bc3c)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f651)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff81324e64)
Location: include/linux/mm.h:895
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
In fs/proc/task_mmu.c (ffffffff813305de)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff81365c51)
Location: include/linux/mm.h:895
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
In fs/ext4/inode.c (ffffffff813729ce)
Location: include/linux/mm.h:895
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
In fs/ext4/mballoc.c (ffffffff8137b98a)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81380c78)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8138943e)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813a49c6)
Location: include/linux/mm.h:895
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813af889)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813b8cfb)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813bb812)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf33e)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfff8)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813d05d1)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813dc280)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813e4fd4)
Location: include/linux/mm.h:895
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
In fs/fuse/readdir.c (ffffffff813ea415)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814453e1)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81499ad7)
Location: include/linux/mm.h:895
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
In block/partition-generic.c (ffffffff814b37b1)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814b6077)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b6b56)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b6fe5)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814b7b51)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b8ed6)
Location: include/linux/mm.h:895
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
In block/partitions/msdos.c (ffffffff814bb156)
Location: include/linux/mm.h:895
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
In block/partitions/osf.c (ffffffff814bb8d3)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bbab4)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbdb8)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bc042)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bc2f6)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814bd274)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd4ec)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a7bf)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8160db9f)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81668217)
Location: include/linux/mm.h:895
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166fcba)
Location: include/linux/mm.h:895
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170b1b0)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8170e400)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81763ade)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff81821ca7)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff8182ee0c)
Location: include/linux/mm.h:895
Inline: True
```
```
In net/core/sock.c (ffffffff81897c0b)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818a2772)
Location: include/linux/mm.h:895
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
In net/core/dev.c (ffffffff818ae963)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818d968d)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818e19d9)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818e4e1a)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818e6b1a)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81929a3c)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81934891)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81976a2e)
Location: include/linux/mm.h:895
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a05b5b)
Location: include/linux/mm.h:895
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
In init/do_mounts.c (ffffffff8289a755)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a0374)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81101719)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8113ed25)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f64bd)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120819f)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8120f407)
Location: include/linux/mm.h:959
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
In mm/filemap.c (ffffffff812164c1)
Location: include/linux/mm.h:959
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
In mm/page-writeback.c (ffffffff81220888)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81222144)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81223fd2)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81225f00)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122d12d)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8123548a)
Location: include/linux/mm.h:959
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8124af9c)
Location: include/linux/mm.h:959
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
In mm/memory.c (ffffffff81256960)
Location: include/linux/mm.h:959
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
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff812575af)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812589ed)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126598e)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8126c04c)
Location: include/linux/mm.h:959
Inline: True
```
```
In mm/madvise.c (ffffffff8127544a)
Location: include/linux/mm.h:959
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
In mm/swap_state.c (ffffffff81277e60)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127c8a0)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8127fe5c)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812881bf)
Location: include/linux/mm.h:959
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
```
```
In mm/mempolicy.c (ffffffff8128b420)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81292209)
Location: include/linux/mm.h:959
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
In mm/memory_hotplug.c (ffffffff8129c5ca)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a13c6)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
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
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a88d3)
Location: include/linux/mm.h:959
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
In mm/khugepaged.c (ffffffff812ac2e5)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b4599)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ba74a)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812be99f)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c0571)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c19f1)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1ec0)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812c2597)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
```
```
In fs/read_write.c (ffffffff812c9d09)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d3712)
Location: include/linux/mm.h:959
Inline: True
```
```
In fs/pipe.c (ffffffff812d57da)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d8267)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812fa502)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813052e7)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81310c91)
Location: include/linux/mm.h:959
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
In fs/block_dev.c (ffffffff81312b43)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81316d2b)
Location: include/linux/mm.h:959
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
In fs/mpage.c (ffffffff81318a94)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8132a916)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff813318c2)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff8134352f)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346e86)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd77)
Location: include/linux/mm.h:959
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
In fs/proc/task_mmu.c (ffffffff81358408)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8138ef70)
Location: include/linux/mm.h:959
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
In fs/ext4/inode.c (ffffffff8139bde2)
Location: include/linux/mm.h:959
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
In fs/ext4/mballoc.c (ffffffff813a2c9a)
Location: include/linux/mm.h:959
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
In fs/ext4/move_extent.c (ffffffff813a9fac)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b360d)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ceba5)
Location: include/linux/mm.h:959
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813d9dd9)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e3b24)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e60ad)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9c96)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fabe7)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb09f)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814070a4)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81410a47)
Location: include/linux/mm.h:959
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
In fs/fuse/readdir.c (ffffffff81416af4)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8147305d)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c76d2)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_pc_page
```
```
In block/partition-generic.c (ffffffff814e1d3b)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e45d7)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4fba)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e5598)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e6125)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7bad)
Location: include/linux/mm.h:959
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
In block/partitions/msdos.c (ffffffff814e97e9)
Location: include/linux/mm.h:959
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
In block/partitions/osf.c (ffffffff814e9ef0)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea113)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea425)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea6b2)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ea994)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814eb928)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ebb9c)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e50e)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81641d4a)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8169dc8b)
Location: include/linux/mm.h:959
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816a5738)
Location: include/linux/mm.h:959
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817467e2)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81749bc9)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817a1875)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8186481a)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81871430)
Location: include/linux/mm.h:959
Inline: True
```
```
In net/core/sock.c (ffffffff818e2145)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818ed2de)
Location: include/linux/mm.h:959
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
In net/core/dev.c (ffffffff818fa251)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8192b853)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819301cc)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81934741)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819364de)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8198cc37)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8199855e)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e05b8)
Location: include/linux/mm.h:959
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a754a9)
Location: include/linux/mm.h:959
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
In init/do_mounts.c (ffffffff8289d73a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a69e2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110db49)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114a74f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8120347b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8121550f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121ca4a)
Location: include/linux/mm.h:972
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
In mm/filemap.c (ffffffff81223dd1)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (ffffffff8122e338)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8122fbf4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81231d62)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81233bb2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123a5be)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff812436ca)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125948c)
Location: include/linux/mm.h:972
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
In mm/memory.c (ffffffff81264ef0)
Location: include/linux/mm.h:972
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
In mm/mincore.c (ffffffff81265aff)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81266ebd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812742a3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127ae5c)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (ffffffff812842b8)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (ffffffff81287950)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128c37b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8128f2e5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81297dbf)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (ffffffff8129af90)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a1f89)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (ffffffff812ac029)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b059e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9e53)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (ffffffff812be83b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c5eb9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812cc62a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d0900)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d24c2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812d3921)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3df0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812d44d0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812db7e7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e52a2)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (ffffffff812e734a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e9dd7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130c282)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81318377)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff813213a8)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (ffffffff81325a83)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81329ba9)
Location: include/linux/mm.h:972
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
In fs/mpage.c (ffffffff8132b8d4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8133dab6)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81341098)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134f725)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8135132e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff8135b96d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f194)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff81365047)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (ffffffff81370658)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff813a79d0)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (ffffffff813b48ea)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (ffffffff813bbafa)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (ffffffff813c2edc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813cc85c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e8275)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813eef54)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813f3e08)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813fdb54)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81400110)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81403d36)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81414ab7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81414f6f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81421e84)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8142a657)
Location: include/linux/mm.h:972
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
In fs/fuse/readdir.c (ffffffff81430a30)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148cdfd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814e0635)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814fb0fa)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814fd997)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe531)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fe968)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814ff4f5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81500f7d)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (ffffffff81502bad)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (ffffffff815032b0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815034d3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815037e5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503a72)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81503d50)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81504ce8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81504f5c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660a78)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8166430a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816c09fb)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816c8468)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a932)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8176dd19)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817c6835)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d32df)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8189655a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818a3230)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (ffffffff81914308)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8191f3fb)
Location: include/linux/mm.h:972
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
In net/core/dev.c (ffffffff8192c391)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8195db8f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81962429)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819674ed)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819694ae)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819c35d7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819cf162)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a175e8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2521b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_devmap_managed_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125e510)
Location: mm/swap.c:1154
Inline: False
Direct callers:
  - init/do_mounts.c:put_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
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
  - mm/page-writeback.c:write_one_page
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:put_compound_head
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
  - mm/mincore.c:mincore_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:try_to_unmap_one
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
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
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
  - mm/mempolicy.c:lookup_node
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
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/memremap.c:memunmap_pages
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
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
  - fs/block_dev.c:blkdev_write_end
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
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:release_buffer_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/partitions/core.c:read_part_sector
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
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
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_build_skb
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
  - net/core/skmsg.c:sk_msg_free_elem
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
```
**Symbols:**

```
ffffffff8125e510-ffffffff8125e568: put_devmap_managed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_devmap_managed_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812685d0)
Location: mm/swap.c:1147
Inline: False
Direct callers:
  - init/do_mounts.c:put_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
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
  - mm/page-writeback.c:write_one_page
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
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
  - mm/mempolicy.c:lookup_node
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
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
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
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/memremap.c:memunmap_pages
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
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
  - fs/block_dev.c:blkdev_write_end
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
  - fs/direct-io.c:dio_zero_block
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:release_buffer_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/partitions/core.c:read_part_sector
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
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
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_build_skb
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
  - net/core/skmsg.c:sk_msg_free_elem
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
```
**Symbols:**

```
ffffffff812685d0-ffffffff81268625: put_devmap_managed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_devmap_managed_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126df60)
Location: mm/swap.c:1148
Inline: False
Direct callers:
  - init/do_mounts.c:put_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
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
  - mm/page-writeback.c:write_one_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
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
  - mm/mempolicy.c:do_get_mempolicy
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
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
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
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/memremap.c:memunmap_pages
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
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
  - fs/block_dev.c:blkdev_write_end
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
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:release_buffer_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/partitions/core.c:read_part_sector
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
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
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - lib/buildid.c:build_id_parse
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_build_skb
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff8126df60-ffffffff8126dfb5: put_devmap_managed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_devmap_managed_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812aaeb0)
Location: mm/swap.c:1139
Inline: False
Direct callers:
  - init/do_mounts.c:put_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
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
  - mm/page-writeback.c:write_one_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:read_cache_pages_invalidate_page
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
  - mm/memory.c:put_page
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
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
  - mm/mempolicy.c:lookup_node
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
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
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
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - mm/memremap.c:memunmap_pages
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
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
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:release_buffer_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fill_write_pages
  - fs/fuse/file.c:fuse_send_write_pages
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete_req
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/fops.c:blkdev_write_end
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/partitions/core.c:read_part_sector
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_vmdb
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
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
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/efi.c:read_lba
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - lib/buildid.c:build_id_parse
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_build_skb
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
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
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff812aaeb0-ffffffff812aaf02: put_devmap_managed_page (STB_GLOBAL)
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
In init/do_mounts.c (ffffffff81e43a9e)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - init/do_mounts.c:put_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db78)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f807)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810d30ee)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff811579ae)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811b2787)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff812cdbfa)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e67f7)
Location: include/linux/mm.h:1149
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
In mm/filemap.c (ffffffff812f3518)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/readahead.c (ffffffff813019a1)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff813053e8)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff8130805d)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff8130d9ab)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff81319939)
Location: include/linux/mm.h:1149
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
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
```
```
In mm/compaction.c (ffffffff81330ec3)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8133796d)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff813480fd)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff81349612)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/memory_hotplug.c (ffffffff81374263)
Location: include/linux/mm.h:1149
Inline: True
```
```
In mm/madvise.c (ffffffff81376b0f)
Location: include/linux/mm.h:1149
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
In mm/swap_state.c (ffffffff8137c139)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813828e4)
Location: include/linux/mm.h:1149
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
In mm/zswap.c (ffffffff81385973)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8139461e)
Location: include/linux/mm.h:1149
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
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff81396e53)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff813a319c)
Location: include/linux/mm.h:1149
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
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff813b601e)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff813b645b)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_finalize
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1a68)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c833b)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff813d3001)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd40f)
Location: include/linux/mm.h:1149
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
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff813e1e65)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813e3ae0)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5a4e)
Location: include/linux/mm.h:1149
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
In mm/page_idle.c (ffffffff813e67a4)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/exec.c (ffffffff813fb270)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe3ee)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814006ab)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c7cf)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81437bc4)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff814468ee)
Location: include/linux/mm.h:1149
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
In fs/direct-io.c (ffffffff8144a782)
Location: include/linux/mm.h:1149
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
In fs/mpage.c (ffffffff8144bc94)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81464776)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff814722f0)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81474071)
Location: include/linux/mm.h:1149
Inline: True
```
```
In fs/verity/verify.c (ffffffff81474768)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff814860cd)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/inline.c (ffffffff814ddb2d)
Location: include/linux/mm.h:1149
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
In fs/ext4/inode.c (ffffffff814e3f48)
Location: include/linux/mm.h:1149
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
In fs/ext4/mballoc.c (ffffffff814f5421)
Location: include/linux/mm.h:1149
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
In fs/ext4/move_extent.c (ffffffff814ff7a6)
Location: include/linux/mm.h:1149
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a178)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153c648)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff8154e769)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511f3)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555d91)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff815695fc)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff815698fd)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81577123)
Location: include/linux/mm.h:1149
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
In fs/fuse/file.c (ffffffff8157f845)
Location: include/linux/mm.h:1149
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
In fs/fuse/readdir.c (ffffffff81589466)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816009cf)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81670471)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff81673bbc)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8167f0a2)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81695f2c)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff816960e2)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c15)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8169725d)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff8169846b)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a640)
Location: include/linux/mm.h:1149
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
In block/partitions/msdos.c (ffffffff8169bba4)
Location: include/linux/mm.h:1149
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
  - block/partitions/msdos.c:parse_extended
  - block/partitions/msdos.c:parse_extended
```
```
In block/partitions/osf.c (ffffffff8169c58b)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c910)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cc05)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169cfc9)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d3d4)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e3b3)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e702)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff8177663e)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c637a)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c8d78)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81936ae6)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193db51)
Location: include/linux/mm.h:1149
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e6a)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81a63e22)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81b5d66f)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81b68cfb)
Location: include/linux/mm.h:1149
Inline: True
```
```
In net/core/sock.c (ffffffff81bed241)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81bfddcc)
Location: include/linux/mm.h:1149
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
In net/core/filter.c (ffffffff81c44d94)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c51813)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c53951)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81c59008)
Location: include/linux/mm.h:1149
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
In net/core/skmsg.c (ffffffff81c8c110)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81ceed16)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed4b)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c36a)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7b3)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b325)
Location: include/linux/mm.h:1149
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81e1d749)
Location: include/linux/mm.h:1149
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
In init/do_mounts.c (ffffffff83e62329)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f106)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810918f3)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810f1c1c)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8118889d)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811f3627)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81339187)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813502db)
Location: include/linux/mm.h:1201
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
In mm/filemap.c (ffffffff8135d868)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/readahead.c (ffffffff8136c190)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/swap.c (ffffffff8136f57f)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff8137200d)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/shmem.c (ffffffff8138cc4a)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/compaction.c (ffffffff813a76f4)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af00d)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813c059e)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/memory_hotplug.c (ffffffff813f1d36)
Location: include/linux/mm.h:1201
Inline: True
```
```
In mm/madvise.c (ffffffff813f49b1)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f98d9)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc890)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff814036b0)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8141309b)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff814169c4)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81422e15)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
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
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81436172)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8143889b)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443b56)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814497a9)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8145881b)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81464128)
Location: include/linux/mm.h:1201
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
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff81469448)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff8146b4bd)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d5f7)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e2a4)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/exec.c (ffffffff81485331)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8148806e)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8148a87b)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ba03f)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814c5ec5)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff814d59f9)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff814d8e84)
Location: include/linux/mm.h:1201
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
In fs/aio.c (ffffffff814f2373)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81503dde)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062c5)
Location: include/linux/mm.h:1201
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506d64)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff8151991c)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/inline.c (ffffffff81576b72)
Location: include/linux/mm.h:1201
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
In fs/ext4/inode.c (ffffffff8157d54e)
Location: include/linux/mm.h:1201
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
In fs/ext4/mballoc.c (ffffffff81590e41)
Location: include/linux/mm.h:1201
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
In fs/ext4/move_extent.c (ffffffff81599f52)
Location: include/linux/mm.h:1201
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4c9d)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815dad38)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff815eede2)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f235f)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7489)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d1dc)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d52e)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b803)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81625525)
Location: include/linux/mm.h:1201
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
In fs/fuse/readdir.c (ffffffff8162f70a)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816b1936)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8172b811)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8172f6bc)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173c1a2)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/pci/p2pdma.c (ffffffff8191bee1)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ca9)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a1a0f8)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a96986)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9ea81)
Location: include/linux/mm.h:1201
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73437)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81bf3005)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81cf75bb)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d0481b)
Location: include/linux/mm.h:1201
Inline: True
```
```
In net/core/sock.c (ffffffff81d99504)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81da5004)
Location: include/linux/mm.h:1201
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
In net/core/filter.c (ffffffff81dff35a)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e06cd1)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e09105)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e0ef68)
Location: include/linux/mm.h:1201
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
In net/core/skmsg.c (ffffffff81e47362)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81eb1f92)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b90)
Location: include/linux/mm.h:1201
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f264ff)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38d83)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f48394)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81ff4ecb)
Location: include/linux/mm.h:1201
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f08b)
Location: include/linux/mm.h:1201
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
In init/do_mounts.c (ffffffff83682836)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092006)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094830)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810fdb9f)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81199a5d)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff81207dd9)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8136a795)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813814c1)
Location: include/linux/mm.h:1387
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
In mm/swap.c (ffffffff813a169f)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813a41af)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/gup.c (ffffffff813e35ec)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813f52f4)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/memory_hotplug.c (ffffffff814258e3)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427597)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c853)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc99)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff814375ca)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81440d77)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/mempolicy.c (ffffffff81449ee7)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81457f8a)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
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
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8146bd48)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146e59b)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814790a4)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147f7c6)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8148e3e8)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81499bdb)
Location: include/linux/mm.h:1387
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
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff8149e3d7)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a02a0)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/exec.c (ffffffff814ba39f)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf5b)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a4b)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eefbc)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814fb3a6)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8150a944)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff81528fbb)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff8153d5fb)
Location: include/linux/mm.h:1387
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153defe)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff81551210)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/mballoc.c (ffffffff815c637e)
Location: include/linux/mm.h:1387
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
In fs/squashfs/block.c (ffffffff816241b1)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dd2)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a44f)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162faf3)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8164509c)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff816453ed)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81653973)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d895)
Location: include/linux/mm.h:1387
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
In fs/fuse/readdir.c (ffffffff8166797d)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816ea336)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81767691)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4f4)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fd39)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a62c98)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae2197)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aea3f9)
Location: include/linux/mm.h:1387
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d6a)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81c4a25c)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c541cf)
Location: include/linux/mm.h:1387
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
In drivers/md/md.c (ffffffff81d5eeb7)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d8db)
Location: include/linux/mm.h:1387
Inline: True
```
```
In net/core/sock.c (ffffffff81e07824)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81e1eabd)
Location: include/linux/mm.h:1387
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
In net/core/filter.c (ffffffff81e70e2a)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79611)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b774)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e82728)
Location: include/linux/mm.h:1387
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
In net/core/skmsg.c (ffffffff81ea2dca)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81f10641)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f22d53)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8618b)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a70)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f48)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff820716e7)
Location: include/linux/mm.h:1387
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f09e)
Location: include/linux/mm.h:1387
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
In init/do_mounts.c (ffffffff838b18d6)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099376)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd10)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff81106952)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff811a8abd)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/events/core.c (ffffffff81393125)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813aa870)
Location: include/linux/mm.h:1441
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
In mm/swap.c (ffffffff813cb31f)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/truncate.c (ffffffff813cdcff)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/gup.c (ffffffff8140de09)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81415b1a)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
```
```
In mm/memory_hotplug.c (ffffffff81452b35)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swap_state.c (ffffffff81465658)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81469782)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/hugetlb.c (ffffffff8147aea7)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/mempolicy.c (ffffffff8148397b)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81491dd6)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
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
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81496f16)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In mm/migrate_device.c (ffffffff8149ef28)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a1b6d)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ad773)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814bdc55)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c93ca)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff814cd508)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/exec.c (ffffffff814ec91f)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3fb)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f3097)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/splice.c (ffffffff81530098)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8153f494)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff8155de9b)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff81572a5b)
Location: include/linux/mm.h:1441
Inline: True
```
```
In fs/verity/verify.c (ffffffff8157349b)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870f0)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/mballoc.c (ffffffff81601ccc)
Location: include/linux/mm.h:1441
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
In fs/squashfs/block.c (ffffffff8165d251)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff33)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81663779)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e5cc)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e90e)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168cf83)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff816975d5)
Location: include/linux/mm.h:1441
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
In fs/fuse/readdir.c (ffffffff816a1cc1)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81727046)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817a9481)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b54)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2549)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab52c8)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b35587)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3d889)
Location: include/linux/mm.h:1441
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8d9)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81cffbe8)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d078cc)
Location: include/linux/mm.h:1441
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
In drivers/md/md.c (ffffffff81e16127)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81e24d1b)
Location: include/linux/mm.h:1441
Inline: True
```
```
In net/core/sock.c (ffffffff81ec4264)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81edc11d)
Location: include/linux/mm.h:1441
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
In net/core/filter.c (ffffffff81f30501)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f396ab)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3ba04)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81f436bb)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650fa)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81fd4830)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7be3)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d76b)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065de0)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff82075208)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82145867)
Location: include/linux/mm.h:1441
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8217709e)
Location: include/linux/mm.h:1441
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
In init/do_mounts.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In virt/kvm/kvm_main.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/net/ethernet/broadcom/bgmac.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/mm.h:990
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
In init/do_mounts.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In arch/arm/mm/fault-armv.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/binfmt_elf_fdpic.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/mm.h:990
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
In init/do_mounts.c (c000000001344c44)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0ec0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In kernel/exit.c (c0000000001447cc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/futex.c (c00000000021d08c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (c000000000337c4c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000350880)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (c00000000035bcac)
Location: include/linux/mm.h:972
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
In mm/filemap.c (c00000000036751c)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (c000000000375dcc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c000000000378078)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c00000000037b7f8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c00000000037e858)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c000000000388508)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (c0000000003958c0)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (c0000000003b7690)
Location: include/linux/mm.h:972
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
In mm/memory.c (c0000000003c6da8)
Location: include/linux/mm.h:972
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
In mm/mincore.c (c0000000003c7c60)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c0000000003c98f8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003d9870)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (c0000000003e3170)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (c0000000003f28dc)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (c0000000003f7ea4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fe910)
Location: include/linux/mm.h:972
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
In mm/zswap.c (c00000000040404c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (c0000000004109d8)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (c0000000004142f4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (c00000000041ed10)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (c00000000042e2a0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c0000000004368b8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c000000000444254)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (c00000000044b184)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000045701c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c000000000461dd0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (c0000000004686ec)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c00000000046aec8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c934)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046d114)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (c00000000046dc48)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (c0000000004772cc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/exec.c (c000000000484ce8)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (c000000000487964)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c00000000048c830)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c0000000004bf1a8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (c0000000004d17ac)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (c0000000004de96c)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (c0000000004e4fbc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (c0000000004eb314)
Location: include/linux/mm.h:972
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
In fs/mpage.c (c0000000004ed3f0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (c000000000504ea4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c00000000050ab88)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (c00000000051ec64)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c0000000005211e0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c00000000052fccc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338ec)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (c00000000053ce60)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (c00000000054e274)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (c00000000059e5f4)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (c0000000005afd98)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (c0000000005baa18)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (c0000000005c4f7c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (c0000000005d1ef0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f7878)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (c00000000060091c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (c0000000006081a0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c000000000616e60)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619e1c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (c00000000061f54c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (c000000000637134)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c000000000637664)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c000000000649e0c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c000000000655758)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (c00000000065dec8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0000000006edbdc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (c00000000076e79c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (c00000000079679c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c0000000007996c0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a638)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079acc0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bc84)
Location: include/linux/mm.h:972
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
In block/partitions/ldm.c (c00000000079e908)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (c0000000007a0724)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (c0000000007a0ed0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a12e8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1738)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1ab0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1e68)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a3344)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a3700)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d67ec)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (c00000000094bc84)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (c000000000955ce8)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (c000000000a253dc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c000000000a29f38)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (c000000000aa3694)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2cc4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
```
```
In drivers/md/md.c (c000000000bd7358)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (c000000000be4e24)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (c000000000c806d4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c000000000c92568)
Location: include/linux/mm.h:972
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
In net/core/dev.c (c000000000ca50bc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (c000000000ce9888)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c000000000cf1478)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c000000000cf839c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c000000000cfb4e4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (c000000000d7dc30)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d8cd74)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (c000000000df1c2c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (c000000000e056c4)
Location: include/linux/mm.h:972
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
In init/do_mounts.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/page_idle.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In mm/frame_vector.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/libfs.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/direct-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/symlink.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ext4/verity.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/ecryptfs/read_write.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In security/tomoyo/domain.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/amiga.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/atari.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/mac.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/msdos.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/osf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sgi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/ultrix.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/karma.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In block/partitions/sysv68.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/linux/mm.h:990
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/mm.h:990
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
In init/do_mounts.c (ffffffff8288b73a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a0302)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81105d74)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81142d6f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811fba9b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120db5f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121509a)
Location: include/linux/mm.h:972
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
In mm/filemap.c (ffffffff8121c421)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (ffffffff81226988)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81228244)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8122a3b2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8122c202)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81232c0e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8123bd1a)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81251adc)
Location: include/linux/mm.h:972
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
In mm/memory.c (ffffffff8125d540)
Location: include/linux/mm.h:972
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
In mm/mincore.c (ffffffff8125e14f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125f50d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126c8f3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812734ac)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (ffffffff8127c908)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (ffffffff8127fee7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128495b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812878c5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129039f)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (ffffffff81293570)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8129a569)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (ffffffff812a4609)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8b7e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b2433)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (ffffffff812b6e1b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812be499)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c4c0a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c8ee0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812caaa2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812cbf01)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc3d0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ccab0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d3dc7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd882)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (ffffffff812df92a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e23b7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81304862)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81310957)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81319988)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (ffffffff8131e063)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81322189)
Location: include/linux/mm.h:972
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
In fs/mpage.c (ffffffff81323eb4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81336096)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81339678)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (ffffffff81347d05)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8134990e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81353f4d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81357774)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135d627)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (ffffffff81368c38)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139ffb0)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (ffffffff813aceca)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (ffffffff813b40da)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (ffffffff813bb4bc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c4e3c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e0855)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e7534)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ec3e8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f6134)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f86f0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc316)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d097)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d54f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141a464)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81422c37)
Location: include/linux/mm.h:972
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
In fs/fuse/readdir.c (ffffffff81429010)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814853dd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d8c15)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814f36da)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f5f77)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f6b11)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f6f48)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f7ad5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f955d)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (ffffffff814fb18d)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (ffffffff814fb890)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fbab3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbdc5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fc052)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fc330)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814fd2c8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd53c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816268e8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8162a17a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8168644b)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8168deb8)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f022)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81722409)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8178b315)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8183c3da)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818490b0)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (ffffffff818b4308)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818bf3fb)
Location: include/linux/mm.h:972
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
In net/core/dev.c (ffffffff818cc391)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818fdb5f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819023f9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819074bd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8190947e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81963447)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8196efd2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b6c78)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff819c48ab)
Location: include/linux/mm.h:972
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
In init/do_mounts.c (ffffffff828896b7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8108ed2e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810f7009)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811360cf)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811ee7e6)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120092f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81207e0a)
Location: include/linux/mm.h:972
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
In mm/filemap.c (ffffffff8120f60b)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (ffffffff81219af8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8121b384)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8121d4d2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8121f2dc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81225cae)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8122ed1a)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81244b07)
Location: include/linux/mm.h:972
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
In mm/memory.c (ffffffff8124f990)
Location: include/linux/mm.h:972
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
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812505df)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125192d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8125e945)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8126541c)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (ffffffff8126e7b8)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (ffffffff81271c71)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812767cb)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81279725)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128202f)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (ffffffff81285180)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8128c129)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (ffffffff812960d9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129a53e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a37bf)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (ffffffff812a7feb)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812af55d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b5c4a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812b9f20)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812bb9e8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812bcd71)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd240)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812bd920)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812c4a47)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce502)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (ffffffff812d056a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d2ff7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812f5482)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81301567)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8130a548)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (ffffffff8130ec03)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81312d29)
Location: include/linux/mm.h:972
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
In fs/mpage.c (ffffffff81314a54)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81326d86)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8132a3a8)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (ffffffff813389e5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8133a5ee)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81344c0d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81348424)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134e2c7)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (ffffffff81359f03)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff81390a40)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (ffffffff8139d95a)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (ffffffff813a4b6a)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (ffffffff813abf4c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b58bc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813d12d5)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813d7fb4)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813dce68)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e6bb4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e9170)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecd96)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdb17)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fdfcf)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140aee4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814136b7)
Location: include/linux/mm.h:972
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
In fs/fuse/readdir.c (ffffffff81419a90)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81475dfd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c95c5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814e3bea)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e6487)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e7021)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e7458)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e7fe5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9a6d)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (ffffffff814eb69d)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (ffffffff814ebda0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ebfc3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec2d5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec562)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ec840)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814ed7d8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814eda4c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161af68)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816643a4)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166b8a8)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8452)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff816fb839)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8176ac65)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d38f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff81803a3a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81810710)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (ffffffff8186e258)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8187933b)
Location: include/linux/mm.h:972
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
In net/core/dev.c (ffffffff81886421)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b798f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818bc229)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818c12cd)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818c328e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8191cf37)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81928ac2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81973a68)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff8198169b)
Location: include/linux/mm.h:972
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
In init/do_mounts.c (ffffffff8289e73a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a02b2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81104019)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81140c1f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f986b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120b8ff)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81212e3a)
Location: include/linux/mm.h:972
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
In mm/filemap.c (ffffffff8121a1c1)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (ffffffff81224728)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81225fe4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81228152)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81229fa2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812309ae)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff81239aba)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8124f87c)
Location: include/linux/mm.h:972
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
In mm/memory.c (ffffffff8125b2e0)
Location: include/linux/mm.h:972
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
In mm/mincore.c (ffffffff8125beef)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125d2ad)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126a693)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127124c)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (ffffffff8127a6a8)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (ffffffff8127dd40)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128276b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812856d5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128e1af)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (ffffffff81291380)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81298379)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (ffffffff812a2419)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a698e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b0243)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (ffffffff812b4c2b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812bc2a9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2a1a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812c6cf0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c88b2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c9d11)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca1e0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ca8c0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d1bd7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db692)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (ffffffff812dd73a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e01c7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81302652)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8130e747)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81317458)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (ffffffff8131bb33)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8131fc59)
Location: include/linux/mm.h:972
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
In fs/mpage.c (ffffffff81321984)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81333b66)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff81337148)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (ffffffff813457d5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff813473de)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81351a1d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81355244)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135b0f7)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (ffffffff81366708)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139d810)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (ffffffff813aa72a)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (ffffffff813b193a)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (ffffffff813b8d1c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c22cc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ddbd5)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e48b4)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813e9768)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f34b4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f5a70)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9696)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a417)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a8cf)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81416604)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8141edd7)
Location: include/linux/mm.h:972
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
In fs/fuse/readdir.c (ffffffff814251b0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148147d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d4ca5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814ef76a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f2007)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2ba1)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f2fd8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f3b65)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f55ed)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (ffffffff814f721d)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (ffffffff814f7920)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7b43)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7e55)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f80e2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f83c0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814f9358)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f95cc)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816548b8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8165814a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816b4af4)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816bc128)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175ddf2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff817611d9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817bb6b5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c815f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8188ba0a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818986e0)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (ffffffff81905308)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819103fb)
Location: include/linux/mm.h:972
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
In net/core/dev.c (ffffffff8191d391)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8194eb8f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81953429)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819584ed)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8195a4ae)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819cdc17)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d97a2)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a216f8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f32b)
Location: include/linux/mm.h:972
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
In init/do_mounts.c (ffffffff8289e73f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a8236)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110f409)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114de7a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8120831f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8121a70f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81221db1)
Location: include/linux/mm.h:972
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
In mm/filemap.c (ffffffff81229298)
Location: include/linux/mm.h:972
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
In mm/page-writeback.c (ffffffff812339f8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812352e4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff81237492)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8123938f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123fdfe)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff812491aa)
Location: include/linux/mm.h:972
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
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125f1ec)
Location: include/linux/mm.h:972
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
In mm/memory.c (ffffffff8126acaa)
Location: include/linux/mm.h:972
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
In mm/mincore.c (ffffffff8126b8df)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8126cc9d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8127a071)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81280cbc)
Location: include/linux/mm.h:972
Inline: True
```
```
In mm/madvise.c (ffffffff8128a288)
Location: include/linux/mm.h:972
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
In mm/swap_state.c (ffffffff8128d8f0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81292452)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81294cf9)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129df4d)
Location: include/linux/mm.h:972
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
```
```
In mm/mempolicy.c (ffffffff812a118e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a8171)
Location: include/linux/mm.h:972
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
In mm/memory_hotplug.c (ffffffff812b2779)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b6cbe)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812c0583)
Location: include/linux/mm.h:972
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
In mm/khugepaged.c (ffffffff812c4a66)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812cca7a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d34ba)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffffffff812d733e)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d956f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812daa0c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812daee0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812db5f0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812e2a15)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec626)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/pipe.c (ffffffff812ee6ba)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812f1aa7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81313c72)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8131ff47)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81329048)
Location: include/linux/mm.h:972
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
In fs/block_dev.c (ffffffff8132d913)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81331979)
Location: include/linux/mm.h:972
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
In fs/mpage.c (ffffffff813336e4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81345bd4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8134a208)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/verity/enable.c (ffffffff81358ab5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8135a6de)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81364fb8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8136881f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8136e873)
Location: include/linux/mm.h:972
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
In fs/proc/task_mmu.c (ffffffff81379a46)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b1d80)
Location: include/linux/mm.h:972
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
In fs/ext4/inode.c (ffffffff813bf017)
Location: include/linux/mm.h:972
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
In fs/ext4/mballoc.c (ffffffff813c646e)
Location: include/linux/mm.h:972
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
In fs/ext4/move_extent.c (ffffffff813cda3c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813d7448)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813f2ff5)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813f9cf1)
Location: include/linux/mm.h:972
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ff06c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff814090c4)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8140b6c0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f2f1)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8142011b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8142058f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142d364)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81435b37)
Location: include/linux/mm.h:972
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
In fs/fuse/readdir.c (ffffffff8143c087)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81499001)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814ed855)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff815087fa)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8150b067)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150bc01)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150c038)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8150cbc5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e64d)
Location: include/linux/mm.h:972
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
In block/partitions/msdos.c (ffffffff8151027d)
Location: include/linux/mm.h:972
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
In block/partitions/osf.c (ffffffff81510980)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510ba3)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510eb5)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81511142)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81511420)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815123b8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8151262c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f338)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8167274a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816ced9b)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816d6a18)
Location: include/linux/mm.h:972
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779452)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8177c839)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817d46f0)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e23ff)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff818aac7a)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818b5740)
Location: include/linux/mm.h:972
Inline: True
```
```
In net/core/sock.c (ffffffff819263f8)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8193155b)
Location: include/linux/mm.h:972
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
In net/core/dev.c (ffffffff8193e8b1)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8197055f)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81974f3c)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8197a61d)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197c6ce)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819d77a7)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e3402)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2ca48)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ac7b)
Location: include/linux/mm.h:972
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
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
</ul>
