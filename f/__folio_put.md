# Function: <code>__folio_put</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __folio_put(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136e890)
Location: mm/swap.c:122
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
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
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_free_folio
  - mm/page-writeback.c:folio_write_one
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
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
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
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
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/mincore.c:mincore_page
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
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:do_get_mempolicy
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
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
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
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:release_buffer_page
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/fops.c:blkdev_write_end
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
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
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_xdp_one
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/gro.c:gro_pull_from_frag0
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
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:dfrag_clear
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8136e890-ffffffff8136e911: __folio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __folio_put(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a0ab0)
Location: mm/swap.c:122
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
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
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_free_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
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
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_page
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/memory_hotplug.c:do_migrate_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
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
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:do_get_mempolicy
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
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
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
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
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
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/fops.c:blkdev_write_end
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
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
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_xdp_one
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
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/gro.c:gro_pull_from_frag0
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
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:dfrag_clear
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813a0ab0-ffffffff813a0b31: __folio_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __folio_put(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813ca730)
Location: mm/swap.c:122
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_folio
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
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_get_entry
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:folio_end_private_2
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:replace_page_cache_folio
  - mm/filemap.c:filemap_free_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:reclaim_folio_list
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
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
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_get_partial_folio
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:copy_pte_range
  - mm/mincore.c:mincore_page
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/memory_hotplug.c:do_migrate_range
  - mm/slub.c:free_large_kmalloc
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
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
  - mm/zswap.c:zswap_writeback_entry
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:do_get_mempolicy
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
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:migrate_folio_done
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_finalize
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_folio
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
  - fs/libfs.c:simple_write_end
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/mpage.c:mpage_readahead
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_migrate_folio
  - fs/aio.c:aio_free_ring
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/coredump.c:dump_user_range
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_delalloc_release
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:ifs_free
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
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
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/fops.c:blkdev_write_end
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
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
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/grant-table.c:gnttab_handle_deferred
  - drivers/char/virtio_console.c:free_buf
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/tun.c:tun_xdp_one
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
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:__xdp_return
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
  - net/mptcp/protocol.c:dfrag_clear
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813ca730-ffffffff813ca7b5: __folio_put (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
