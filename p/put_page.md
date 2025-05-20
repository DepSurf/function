# Function: <code>put_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119d470)
Location: mm/swap.c:272
Inline: True
Direct callers:
  - init/do_mounts.c:mount_block_root
  - kernel/exit.c:do_exit
  - kernel/power/swap.c:hib_end_io
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_notify_resume
  - mm/filemap.c:wait_on_page_read
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
  - mm/page-writeback.c:write_one_page
  - mm/readahead.c:read_cache_pages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/swap.c:__get_page_tail
  - mm/swap.c:put_pages_list
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__do_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/mincore.c:mincore_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:swapin_readahead
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:putback_active_hugepage
  - mm/mempolicy.c:do_get_mempolicy
  - mm/ksm.c:break_ksm
  - mm/ksm.c:break_ksm
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
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
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__split_huge_page_pmd
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
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:put_hwpoison_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/page_idle.c:page_idle_get_page
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/frame_vector.c:put_vaddr_frames
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
  - fs/namei.c:page_put_link
  - fs/namei.c:page_readlink
  - fs/libfs.c:simple_write_end
  - fs/splice.c:page_cache_pipe_buf_release
  - fs/splice.c:spd_release_page
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/block_dev.c:blkdev_write_end
  - fs/direct-io.c:dio_bio_complete
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
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:mpage_readpages
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/read_write.c:ecryptfs_write
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - security/tomoyo/domain.c:tomoyo_dump_page
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/partition-generic.c:read_dev_sector
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
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
  - drivers/scsi/scsicam.c:scsi_bios_ptable
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - net/core/sock.c:sk_common_release
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_shift
  - net/core/dev.c:gro_pull_from_frag0
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff8119d470-ffffffff8119d4b3: put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81f82489)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/gup.c (ffffffff8107139b)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:undo_dev_pagemap
```
```
In kernel/exit.c (ffffffff81087059)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810d761b)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81107744)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/trace/trace.c (ffffffff811586d3)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/events/uprobes.c (ffffffff8119adcd)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811a1441)
Location: include/linux/mm.h:775
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
  - mm/filemap.c:delete_from_page_cache
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page-writeback.c (ffffffff811afd8f)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811b1149)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811b2fd9)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff811b468a)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811b9392)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811c31b3)
Location: include/linux/mm.h:775
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
  - mm/shmem.c:shmem_write_end
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
```
```
In mm/gup.c (ffffffff811d51bf)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d669f)
Location: include/linux/mm.h:775
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
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mincore.c (ffffffff811de0c5)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff811df08f)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811e8365)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff811edb9d)
Location: include/linux/mm.h:775
Inline: True
```
```
In mm/madvise.c (ffffffff811ef570)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff811f0b4f)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811f4736)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff811f700c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff811fe297)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff811ffac3)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204d40)
Location: include/linux/mm.h:775
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
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81894116)
Location: include/linux/mm.h:775
Inline: True
```
```
In mm/migrate.c (ffffffff81213329)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
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
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81218092)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
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
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121b84f)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81221261)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81227f48)
Location: include/linux/mm.h:775
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff8122b674)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8122d390)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8122df31)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8122e4a5)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/exec.c (ffffffff81239d4e)
Location: include/linux/mm.h:775
Inline: True
```
```
In fs/pipe.c (ffffffff8123ba9d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8123f23a)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8125d01c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81267010)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:spd_release_page
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8126c87a)
Location: include/linux/mm.h:775
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
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/block_dev.c (ffffffff812703cb)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8127470f)
Location: include/linux/mm.h:775
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
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff81276e99)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81285178)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff81287d81)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In fs/binfmt_elf.c (ffffffff81295981)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8129860d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8129bdf4)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff812a5457)
Location: include/linux/mm.h:775
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cd15e)
Location: include/linux/mm.h:775
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
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/symlink.c (ffffffff812edf92)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff81303cdc)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff81306ed7)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff813114c3)
Location: include/linux/mm.h:775
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
In fs/ext4/readpage.c (ffffffff81313107)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/commit.c (ffffffff81318a5b)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813223fe)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81324da8)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813286bb)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8133883c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81338b44)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81343e6d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_finish
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134dadb)
Location: include/linux/mm.h:775
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
In security/tomoyo/domain.c (ffffffff813a4261)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff813f654c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff8141147e)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8141361d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81413dd8)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81414a0d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814150d8)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81416867)
Location: include/linux/mm.h:775
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
In block/partitions/msdos.c (ffffffff814184f0)
Location: include/linux/mm.h:775
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
In block/partitions/osf.c (ffffffff81418c3b)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81418e3c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8141911b)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81419325)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81419578)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8141a68d)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8141a8d0)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513fca)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81569650)
Location: include/linux/mm.h:775
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff81570d59)
Location: include/linux/mm.h:775
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff81601257)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/virtio_net.c (ffffffff81652444)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/md/md.c (ffffffff816f6006)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/bitmap.c (ffffffff816fd4f8)
Location: include/linux/mm.h:775
Inline: True
```
```
In net/core/sock.c (ffffffff8176ab9c)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
```
```
In net/core/skbuff.c (ffffffff81773dd9)
Location: include/linux/mm.h:775
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
In net/core/dev.c (ffffffff8177dcf8)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff817e15c6)
Location: include/linux/mm.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff81199290-ffffffff811992e0: put_page (STB_LOCAL)
ffffffff8119f750-ffffffff8119f7a0: put_page (STB_LOCAL)
ffffffff811d6320-ffffffff811d6370: put_page (STB_LOCAL)
ffffffff812138e0-ffffffff81213930: put_page (STB_LOCAL)
ffffffff81225f10-ffffffff81225f60: put_page (STB_LOCAL)
ffffffff81342100-ffffffff81342150: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81fbe527)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/mm/gup.c (ffffffff81074f1b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:undo_dev_pagemap
```
```
In kernel/exit.c (ffffffff8108bfc5)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810de193)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8110ef1b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811aa52d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/filemap.c (ffffffff811b1167)
Location: include/linux/mm.h:764
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
  - mm/filemap.c:delete_from_page_cache
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/page-writeback.c (ffffffff811c044f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811c1727)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811c3649)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff811c4d0f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811c99c2)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811d3232)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
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
```
```
In mm/gup.c (ffffffff811e51da)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ed5e2)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
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
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
```
```
In mm/mincore.c (ffffffff811eded5)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff811eeea5)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811f962e)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff811fe49b)
Location: include/linux/mm.h:764
Inline: True
```
```
In mm/madvise.c (ffffffff811ffef0)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:SyS_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8120154f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81205260)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff812079bc)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8120ed67)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/mempolicy.c (ffffffff81211394)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216a25)
Location: include/linux/mm.h:764
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff818c8814)
Location: include/linux/mm.h:764
Inline: True
```
```
In mm/migrate.c (ffffffff81225691)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
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
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a632)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
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
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122cfed)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812339ad)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8123a4f2)
Location: include/linux/mm.h:764
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff8123dbd8)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8123f8b6)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff81240481)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812409d5)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff8124476c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8124ca8c)
Location: include/linux/mm.h:764
Inline: True
```
```
In fs/pipe.c (ffffffff8124e83d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8125200a)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81270553)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8127a047)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:spd_release_page
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8127f8da)
Location: include/linux/mm.h:764
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
In fs/block_dev.c (ffffffff8128582b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81287b39)
Location: include/linux/mm.h:764
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
  - fs/direct-io.c:dio_bio_complete
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128ab5c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81299388)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/dax.c (ffffffff8129afbf)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
```
In fs/binfmt_elf.c (ffffffff812aa5df)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812ad09d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812b1661)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff812badac)
Location: include/linux/mm.h:764
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e2eda)
Location: include/linux/mm.h:764
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
In fs/ext4/symlink.c (ffffffff81303f3c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ext4/mballoc.c (ffffffff81319c9c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffff8131ce7b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff8132739d)
Location: include/linux/mm.h:764
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
In fs/ext4/readpage.c (ffffffff813290ab)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/commit.c (ffffffff8132ea4f)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8133828e)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8133ac08)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e408)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e5dc)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e8e4)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813596d8)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_finish
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813633ef)
Location: include/linux/mm.h:764
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
In security/tomoyo/domain.c (ffffffff813baddc)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8140ff2c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff8142c818)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8142eb4d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8142f308)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8142ff3d)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff81430608)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81431d97)
Location: include/linux/mm.h:764
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
In block/partitions/msdos.c (ffffffff81433a20)
Location: include/linux/mm.h:764
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
In block/partitions/osf.c (ffffffff8143416b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8143436c)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8143464b)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81434855)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81434aa8)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81435bbd)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81435e00)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815403fa)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81595d90)
Location: include/linux/mm.h:764
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8159d419)
Location: include/linux/mm.h:764
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff81630947)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/md/md.c (ffffffff81727832)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/bitmap.c (ffffffff8172f178)
Location: include/linux/mm.h:764
Inline: True
```
```
In net/core/sock.c (ffffffff81796c3e)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff817a1004)
Location: include/linux/mm.h:764
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
In net/core/dev.c (ffffffff817ab668)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81811a96)
Location: include/linux/mm.h:764
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff811a8c80-ffffffff811a8cd0: put_page (STB_LOCAL)
ffffffff811af170-ffffffff811af1c0: put_page (STB_LOCAL)
ffffffff811e62b0-ffffffff811e6300: put_page (STB_LOCAL)
ffffffff81225c70-ffffffff81225cc0: put_page (STB_LOCAL)
ffffffff812384f0-ffffffff81238540: put_page (STB_LOCAL)
ffffffff81285dd0-ffffffff81285e20: put_page (STB_LOCAL)
ffffffff81357bc0-ffffffff81357c10: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8209e669)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810891a4)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810dd2a2)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81110258)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b28e5)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811b5090)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811b85b6)
Location: include/linux/mm.h:809
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
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c85e0)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811c9a40)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811cbaaa)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff811cd036)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d2488)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811da8ac)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mcopy_atomic_pte
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
```
```
In mm/gup.c (ffffffff811f0d5a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f85df)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff811f8f03)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff811f9e72)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81204433)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81209096)
Location: include/linux/mm.h:809
Inline: True
```
```
In mm/madvise.c (ffffffff8120aee1)
Location: include/linux/mm.h:809
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
In mm/swap_state.c (ffffffff8120c3f6)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81210803)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff81212989)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8121a606)
Location: include/linux/mm.h:809
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
In mm/mempolicy.c (ffffffff8121ccc5)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812224a1)
Location: include/linux/mm.h:809
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
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff818ffe27)
Location: include/linux/mm.h:809
Inline: True
```
```
In mm/migrate.c (ffffffff81230d9c)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
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
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812362c6)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
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
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81239758)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8123f243)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8124605c)
Location: include/linux/mm.h:809
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff81248b6d)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8124b51a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8124c2fc)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8124c76e)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff81250199)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff81258b30)
Location: include/linux/mm.h:809
Inline: True
```
```
In fs/pipe.c (ffffffff8125a798)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8125da25)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8127dc73)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81287585)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8128d0e7)
Location: include/linux/mm.h:809
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
In fs/block_dev.c (ffffffff81292cd2)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81295566)
Location: include/linux/mm.h:809
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
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/mpage.c (ffffffff812979ac)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812a7067)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff812b6de5)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9ec4)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812bea7d)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff812c7f61)
Location: include/linux/mm.h:809
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fb21c)
Location: include/linux/mm.h:809
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
In fs/ext4/inode.c (ffffffff81307463)
Location: include/linux/mm.h:809
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
In fs/ext4/mballoc.c (ffffffff81310f9f)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/move_extent.c (ffffffff81315980)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff8131e89f)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8133918e)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/commit.c (ffffffff81343c1f)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8134cf9a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8134f8dd)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813530cc)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81363162)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813633fb)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8136def9)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81377d57)
Location: include/linux/mm.h:809
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
In security/tomoyo/domain.c (ffffffff813d166f)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8141d8a9)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff81439b3a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8143be84)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8143c6bb)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8143cfa5)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8143d6e8)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8143ed57)
Location: include/linux/mm.h:809
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
In block/partitions/msdos.c (ffffffff814409a8)
Location: include/linux/mm.h:809
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
In block/partitions/osf.c (ffffffff81440dd3)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81440fc0)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81441247)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8144141c)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8144161f)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8144261e)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8144281a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81554235)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff815a9bbf)
Location: include/linux/mm.h:809
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff815b1478)
Location: include/linux/mm.h:809
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff816455b2)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/md/md.c (ffffffff817400f6)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/bitmap.c (ffffffff817487ee)
Location: include/linux/mm.h:809
Inline: True
```
```
In net/core/sock.c (ffffffff817b503a)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff817be10a)
Location: include/linux/mm.h:809
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
In net/core/dev.c (ffffffff817c9cd8)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81831e28)
Location: include/linux/mm.h:809
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff811f8e47-ffffffff811f8e65: put_page (STB_LOCAL)
ffffffff8121ff10-ffffffff8121ff31: put_page (STB_LOCAL)
ffffffff812311d0-ffffffff812311f1: put_page (STB_LOCAL)
ffffffff81244050-ffffffff81244071: put_page (STB_LOCAL)
ffffffff8143c290-ffffffff8143c2b1: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff826a463a)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8108fefc)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810e54c3)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8111b9b1)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff811c0124)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811c64fc)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811c9340)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ccd21)
Location: include/linux/mm.h:848
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
In mm/page-writeback.c (ffffffff811dd40e)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811de8cc)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff811e04ba)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff811e2386)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e792f)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811f063f)
Location: include/linux/mm.h:848
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
In mm/gup.c (ffffffff812058c8)
Location: include/linux/mm.h:848
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
In mm/memory.c (ffffffff8121079f)
Location: include/linux/mm.h:848
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
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mincore.c (ffffffff81211217)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812122c2)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8121d211)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812221c6)
Location: include/linux/mm.h:848
Inline: True
```
```
In mm/madvise.c (ffffffff812242a5)
Location: include/linux/mm.h:848
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
In mm/swap_state.c (ffffffff812260f7)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81227cc7)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8122d3c9)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81235776)
Location: include/linux/mm.h:848
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
In mm/mempolicy.c (ffffffff81237e75)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/ksm.c (ffffffff8123d7e2)
Location: include/linux/mm.h:848
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
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memory_hotplug.c (ffffffff81989f63)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124c515)
Location: include/linux/mm.h:848
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
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81255a81)
Location: include/linux/mm.h:848
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
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81257eed)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125ef9b)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81266135)
Location: include/linux/mm.h:848
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff81268d5b)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8126b803)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8126c70c)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cbf6)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff812720b9)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127acb3)
Location: include/linux/mm.h:848
Inline: True
```
```
In fs/pipe.c (ffffffff8127cafc)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81280426)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812a0723)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812a9e89)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812b2009)
Location: include/linux/mm.h:848
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
In fs/block_dev.c (ffffffff812b5b42)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b8717)
Location: include/linux/mm.h:848
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
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812bac2f)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812cad05)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff812da7a3)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd893)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff812e2451)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff812ec150)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8131f9aa)
Location: include/linux/mm.h:848
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
In fs/ext4/inode.c (ffffffff8132c04c)
Location: include/linux/mm.h:848
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
In fs/ext4/mballoc.c (ffffffff81332d29)
Location: include/linux/mm.h:848
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
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff8133a1a1)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81342ec1)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8135d492)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/jbd2/commit.c (ffffffff81368272)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff81371608)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81373f74)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81377c39)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81387df6)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813880cc)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81392ace)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8139caf7)
Location: include/linux/mm.h:848
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
In security/tomoyo/domain.c (ffffffff813f7b33)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81448739)
Location: include/linux/mm.h:848
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
In block/partition-generic.c (ffffffff81465b3a)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff81467e94)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814687c8)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81469172)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814699ad)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8146b147)
Location: include/linux/mm.h:848
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
In block/partitions/msdos.c (ffffffff8146d033)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff8146d5a3)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8146d800)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8146dae7)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8146dd0c)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8146df5f)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8146ef92)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8146f1fa)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7c75)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816104df)
Location: include/linux/mm.h:848
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff81618048)
Location: include/linux/mm.h:848
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff816ae552)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff816ff9d2)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md.c (ffffffff817b27a8)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff817baa76)
Location: include/linux/mm.h:848
Inline: True
```
```
In net/core/sock.c (ffffffff8182d46d)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818377f7)
Location: include/linux/mm.h:848
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
In net/core/dev.c (ffffffff818435d8)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp.c (ffffffff818a69ac)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff818b0feb)
Location: include/linux/mm.h:848
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
**Symbols:**

```
ffffffff81208040-ffffffff8120808b: put_page (STB_LOCAL)
ffffffff8123b130-ffffffff8123b17b: put_page (STB_LOCAL)
ffffffff8124f020-ffffffff8124f06b: put_page (STB_LOCAL)
ffffffff81263eb0-ffffffff81263efb: put_page (STB_LOCAL)
ffffffff812b6280-ffffffff812b62cb: put_page (STB_LOCAL)
ffffffff8132ec80-ffffffff8132eccb: put_page (STB_LOCAL)
ffffffff81468350-ffffffff8146839b: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff826cd73c)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff81093ab2)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810ed996)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811284f7)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/sockmap.c (ffffffff811ceaaf)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In kernel/bpf/stackmap.c (ffffffff811d0d70)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811e06a0)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811e6b90)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811e946e)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ede22)
Location: include/linux/mm.h:928
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
In mm/page-writeback.c (ffffffff811fe565)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff811ffe86)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8120143f)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81203a7e)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8120a9a8)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff81211daf)
Location: include/linux/mm.h:928
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
In mm/gup.c (ffffffff81226bf6)
Location: include/linux/mm.h:928
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
In mm/memory.c (ffffffff812311af)
Location: include/linux/mm.h:928
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
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff81231d4b)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81232ffa)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8123f10e)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812440d0)
Location: include/linux/mm.h:928
Inline: True
```
```
In mm/madvise.c (ffffffff81244ea8)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
Direct callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff812486ac)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124d602)
Location: include/linux/mm.h:928
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
In mm/zswap.c (ffffffff812503e9)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812586b8)
Location: include/linux/mm.h:928
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff8125b34b)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff81260dff)
Location: include/linux/mm.h:928
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
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff819e63ca)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8126fee3)
Location: include/linux/mm.h:928
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
In mm/huge_memory.c (ffffffff81279927)
Location: include/linux/mm.h:928
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
In mm/khugepaged.c (ffffffff8127db66)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8128317c)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8128a4f0)
Location: include/linux/mm.h:928
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff8128dcdf)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8129021b)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812912b6)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812917b2)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff81297ee0)
Location: include/linux/mm.h:928
Inline: True
```
```
In fs/exec.c (ffffffff812a1a63)
Location: include/linux/mm.h:928
Inline: True
```
```
In fs/pipe.c (ffffffff812a3a78)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812a6585)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812c6c83)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812d0319)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812d9f41)
Location: include/linux/mm.h:928
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
In fs/block_dev.c (ffffffff812dc9e2)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812e0db1)
Location: include/linux/mm.h:928
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
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e37af)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff812f3c95)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff813064a2)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81309e47)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff8130e952)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
  - fs/iomap.c:iomap_dirty_actor
  - fs/iomap.c:iomap_dirty_actor
```
```
In fs/proc/task_mmu.c (ffffffff8131998f)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8134daa3)
Location: include/linux/mm.h:928
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
In fs/ext4/inode.c (ffffffff8135a674)
Location: include/linux/mm.h:928
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
In fs/ext4/mballoc.c (ffffffff8135f9d4)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff813687e4)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81370f8e)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8138be27)
Location: include/linux/mm.h:928
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81396b00)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff8139ff5c)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813a2a1c)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813a654f)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a9a)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813b7072)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c2c41)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813cbf06)
Location: include/linux/mm.h:928
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
In security/tomoyo/domain.c (ffffffff81428b03)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8147b9ad)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
```
```
In block/partition-generic.c (ffffffff81499542)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8149bd59)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8149c828)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8149ccb7)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8149d823)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8149eb28)
Location: include/linux/mm.h:928
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
In block/partitions/msdos.c (ffffffff814a0d88)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814a1505)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814a16e6)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814a19e6)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814a1c71)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814a1f28)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814a3086)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814a3302)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f01cb)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff815f25a1)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81649fc9)
Location: include/linux/mm.h:928
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8165195c)
Location: include/linux/mm.h:928
Inline: True
```
```
In drivers/scsi/scsicam.c (ffffffff816ea942)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8173d179)
Location: include/linux/mm.h:928
Inline: True
```
```
In drivers/md/md.c (ffffffff817f5d18)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81802b22)
Location: include/linux/mm.h:928
Inline: True
```
```
In net/core/sock.c (ffffffff81875e1d)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81881cb5)
Location: include/linux/mm.h:928
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
In net/core/dev.c (ffffffff8188dab8)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b3acb)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818baa6f)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818bda2c)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/ipv4/tcp.c (ffffffff818fbaa5)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81906688)
Location: include/linux/mm.h:928
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/xdp/xdp_umem.c (ffffffff819ccaad)
Location: include/linux/mm.h:928
Inline: True
```
**Symbols:**

```
ffffffff81228ee0-ffffffff81228f2e: put_page (STB_LOCAL)
ffffffff81244a30-ffffffff81244a7e: put_page (STB_LOCAL)
ffffffff81258845-ffffffff81258890: put_page (STB_LOCAL)
ffffffff812881b0-ffffffff812881fe: put_page (STB_LOCAL)
ffffffff812ddff0-ffffffff812de03e: put_page (STB_LOCAL)
ffffffff8135d260-ffffffff8135d2ae: put_page (STB_LOCAL)
ffffffff8149c1e0-ffffffff8149c22e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8288371a)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8109bd6d)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810f9006)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81133dd9)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811e08af)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff811f0af4)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff811f76ec)
Location: include/linux/mm.h:979
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
In kernel/memremap.c (ffffffff811fa130)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages_release
```
```
In mm/filemap.c (ffffffff811ff421)
Location: include/linux/mm.h:979
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
In mm/page-writeback.c (ffffffff812111f5)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81212756)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812146ef)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81216371)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121d6ab)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff81223c4c)
Location: include/linux/mm.h:979
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
In mm/gup.c (ffffffff81239cf5)
Location: include/linux/mm.h:979
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
In mm/memory.c (ffffffff8124497f)
Location: include/linux/mm.h:979
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mincore.c (ffffffff8124551b)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812467cf)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81253729)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff812587d0)
Location: include/linux/mm.h:979
Inline: True
```
```
In mm/madvise.c (ffffffff812594fb)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
Direct callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff8125cc82)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81261a11)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_vma
```
```
In mm/zswap.c (ffffffff812648d9)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126cd8a)
Location: include/linux/mm.h:979
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff8126fdf9)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812755d6)
Location: include/linux/mm.h:979
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
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffffffff81a21bd3)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81284596)
Location: include/linux/mm.h:979
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
In mm/huge_memory.c (ffffffff8128df44)
Location: include/linux/mm.h:979
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
In mm/khugepaged.c (ffffffff81291649)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812991ce)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129f459)
Location: include/linux/mm.h:979
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812a361f)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812a4c20)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812a62d6)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a67d2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffff812ad1f6)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b6823)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/pipe.c (ffffffff812b8bc8)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812bb655)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812dbe53)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff812e6669)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff812ef42f)
Location: include/linux/mm.h:979
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
In fs/block_dev.c (ffffffff812f0c32)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f5b5a)
Location: include/linux/mm.h:979
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
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f8456)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81309343)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/binfmt_elf.c (ffffffff8131bc32)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8131f647)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap.c (ffffffff81324e56)
Location: include/linux/mm.h:979
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
In fs/proc/task_mmu.c (ffffffff813305cf)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff81365c43)
Location: include/linux/mm.h:979
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
In fs/ext4/inode.c (ffffffff813729c0)
Location: include/linux/mm.h:979
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
In fs/ext4/mballoc.c (ffffffff8137b97c)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff81380c6a)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff81389430)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813a49b7)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813af87b)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813b8cec)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813bb804)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf32f)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813cffea)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813d05c2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813dc26d)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff813e4fc6)
Location: include/linux/mm.h:979
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
In fs/fuse/readdir.c (ffffffff813ea406)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814453d3)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff81499ac9)
Location: include/linux/mm.h:979
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
In block/partition-generic.c (ffffffff814b37a2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814b6069)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814b6b48)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814b6fd7)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814b7b43)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814b8ec8)
Location: include/linux/mm.h:979
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
In block/partitions/msdos.c (ffffffff814bb148)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814bb8c5)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814bbaa6)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814bbdaa)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814bc034)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814bc2e8)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814bd266)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814bd4e2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a7b1)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8160db91)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81668209)
Location: include/linux/mm.h:979
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166fcac)
Location: include/linux/mm.h:979
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170b1a2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8170e3f2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff81763ad0)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff81821c98)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff8182ee02)
Location: include/linux/mm.h:979
Inline: True
```
```
In net/core/sock.c (ffffffff81897bfd)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818a2763)
Location: include/linux/mm.h:979
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
In net/core/dev.c (ffffffff818ae955)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818d967f)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818e19cb)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818e4e0c)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818e6b0b)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81929a2e)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81934882)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81976a18)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a05b4d)
Location: include/linux/mm.h:979
Inline: True
```
**Symbols:**

```
ffffffff8123c6b0-ffffffff8123c6fe: put_page (STB_LOCAL)
ffffffff81258dd0-ffffffff81258e1e: put_page (STB_LOCAL)
ffffffff8126cf19-ffffffff8126cf64: put_page (STB_LOCAL)
ffffffff8129d100-ffffffff8129d14e: put_page (STB_LOCAL)
ffffffff812f35e0-ffffffff812f362e: put_page (STB_LOCAL)
ffffffff81375790-ffffffff813757de: put_page (STB_LOCAL)
ffffffff814b6500-ffffffff814b654e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8289a73b)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a0368)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110170b)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8113ed17)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f64ae)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81208191)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8120f3f9)
Location: include/linux/mm.h:1023
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
In mm/filemap.c (ffffffff812164b3)
Location: include/linux/mm.h:1023
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
In mm/page-writeback.c (ffffffff81220879)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81222136)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff812243af)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81225ef1)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122d120)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8123547b)
Location: include/linux/mm.h:1023
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
In mm/gup.c (ffffffff8124af8e)
Location: include/linux/mm.h:1023
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
In mm/memory.c (ffffffff81256952)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffff8125759f)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff812589df)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81265980)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8126c03e)
Location: include/linux/mm.h:1023
Inline: True
```
```
In mm/madvise.c (ffffffff8127543c)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_willneed
  - mm/madvise.c:swapin_walk_pmd_entry
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81277e52)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127c88a)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8127fe4e)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812881b0)
Location: include/linux/mm.h:1023
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff8128b412)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812921fb)
Location: include/linux/mm.h:1023
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
In mm/memory_hotplug.c (ffffffff8129c5bc)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a13b7)
Location: include/linux/mm.h:1023
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
In mm/huge_memory.c (ffffffff812a88c4)
Location: include/linux/mm.h:1023
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
In mm/khugepaged.c (ffffffff812ac2d7)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b458b)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ba73b)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812be98d)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c0563)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c19e3)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1eb2)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812c2589)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages_release
```
```
In fs/read_write.c (ffffffff812c9cfb)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d3704)
Location: include/linux/mm.h:1023
Inline: True
```
```
In fs/pipe.c (ffffffff812d57c8)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d8255)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812fa4f3)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813052d9)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff81310c7f)
Location: include/linux/mm.h:1023
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
In fs/block_dev.c (ffffffff81312b33)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81316d1d)
Location: include/linux/mm.h:1023
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
In fs/mpage.c (ffffffff81318a87)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8132a908)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff813318b4)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff81343525)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81346e7c)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd69)
Location: include/linux/mm.h:1023
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
In fs/proc/task_mmu.c (ffffffff813583f9)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8138ef61)
Location: include/linux/mm.h:1023
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139bdcf)
Location: include/linux/mm.h:1023
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
In fs/ext4/mballoc.c (ffffffff813a2c8c)
Location: include/linux/mm.h:1023
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
In fs/ext4/move_extent.c (ffffffff813a9f9e)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b35ff)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ceb96)
Location: include/linux/mm.h:1023
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813d9dcb)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e3b16)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e609f)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9c88)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fabd8)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb090)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81407092)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81410a38)
Location: include/linux/mm.h:1023
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
In fs/fuse/readdir.c (ffffffff81416ae5)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8147304f)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c76c4)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_pc_page
```
```
In block/partition-generic.c (ffffffff814e1d2c)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e45c9)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e4fac)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e558a)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e6117)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e7b9f)
Location: include/linux/mm.h:1023
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
In block/partitions/msdos.c (ffffffff814e97db)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814e9ee2)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ea105)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ea417)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ea6a4)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ea986)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814eb91a)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814ebb92)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e500)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81641d3c)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8169dc7c)
Location: include/linux/mm.h:1023
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816a5729)
Location: include/linux/mm.h:1023
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff817467d4)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81749bbb)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817a1867)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8186480b)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81871421)
Location: include/linux/mm.h:1023
Inline: True
```
```
In net/core/sock.c (ffffffff818e2137)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818ed2cf)
Location: include/linux/mm.h:1023
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
In net/core/dev.c (ffffffff818fa243)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8192b845)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819301be)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81934733)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff819364cf)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8198cc29)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8199854f)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e05a2)
Location: include/linux/mm.h:1023
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xdp/xdp_umem.c (ffffffff81a7549a)
Location: include/linux/mm.h:1023
Inline: True
```
**Symbols:**

```
ffffffff812745e0-ffffffff8127462e: put_page (STB_LOCAL)
ffffffff8128832c-ffffffff81288377: put_page (STB_LOCAL)
ffffffff812b82b0-ffffffff812b82fe: put_page (STB_LOCAL)
ffffffff8138cc20-ffffffff8138cc6e: put_page (STB_LOCAL)
ffffffff814e4a40-ffffffff814e4a8e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8289d720)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a69d6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110db3b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114a741)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8120346c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81215501)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121ca3c)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (ffffffff81223dc3)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffffffff8122e329)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8122fbe6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8123213f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81233ba4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123a5b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff812436bb)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffffffff8125947e)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffffffff81264ee2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffff81265aef)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81266eaf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff81274295)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127ae4e)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffff812842aa)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81287942)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128c365)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff8128f2d7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81297db0)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff8129af82)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a1f7b)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (ffffffff812ac01b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b058b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (ffffffff812b9e44)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (ffffffff812be82d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c5eab)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812cc61b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812d08ee)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d24b4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812d3913)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3de2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812d44c2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812db7d9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e5294)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffffffff812e7338)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e9dc5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8130c273)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81318369)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8132139e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffff81325a73)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81329b9b)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffff8132b8c7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff8133daa8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8134108a)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffff8134f717)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81351320)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff8135b963)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f18a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff81365039)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffff81370649)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff813a79c1)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813b48d7)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffff813bbaec)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffff813c2ece)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813cc84e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e8266)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813eef45)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813f3dfa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813fdb46)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81400102)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81403d28)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81414aa8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81414f60)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81421e72)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8142a648)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (ffffffff81430a21)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148cdef)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814e0627)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814fb0eb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814fd989)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814fe523)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814fe95a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814ff4e7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81500f6f)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffff81502b9f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff815032a2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815034c5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815037d7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81503a64)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81503d42)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81504cda)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81504f52)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660a6a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff816642fc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816c09ec)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816c8459)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a924)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8176dd0b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817c6827)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d32d1)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8189654b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818a3221)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffff819142fa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8191f3ec)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffff8192c383)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8195db81)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff8196241b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819674df)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8196949f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819c35c9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819cf153)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a175d2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2520d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff812833f0-ffffffff8128343e: put_page (STB_LOCAL)
ffffffff81297f2c-ffffffff81297f77: put_page (STB_LOCAL)
ffffffff812ca190-ffffffff812ca1de: put_page (STB_LOCAL)
ffffffff813a5670-ffffffff813a56be: put_page (STB_LOCAL)
ffffffff814fde00-ffffffff814fde4e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8100422e)
Location: include/linux/mm.h:1152
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810ae318)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81118b5b)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8115b296)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff8122b1ee)
Location: include/linux/mm.h:1152
Inline: True
```
```
In kernel/events/core.c (ffffffff81231e7a)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81246f5a)
Location: include/linux/mm.h:1152
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
In mm/filemap.c (ffffffff81252c6a)
Location: include/linux/mm.h:1152
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
In mm/page-writeback.c (ffffffff8125a174)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8125cf96)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8125e5cd)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8126137d)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8126a23a)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
```
```
In mm/shmem.c (ffffffff8126f87b)
Location: include/linux/mm.h:1152
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
In mm/gup.c (ffffffff81287bce)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:put_compound_head
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812952b2)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffff81295e27)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff81297124)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812a552f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b5d35)
Location: include/linux/mm.h:1152
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
Direct callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/swap_state.c (ffffffff812b98d9)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812bf359)
Location: include/linux/mm.h:1152
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
In mm/zswap.c (ffffffff812c1f87)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812cb471)
Location: include/linux/mm.h:1152
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
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812cb976)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff812d6e70)
Location: include/linux/mm.h:1152
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
In mm/memory_hotplug.c (ffffffff812e147f)
Location: include/linux/mm.h:1152
Inline: True
```
```
In mm/migrate.c (ffffffff812e3458)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812eea11)
Location: include/linux/mm.h:1152
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
In mm/khugepaged.c (ffffffff812f3d8c)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff812fbb93)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81301e5e)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff81307330)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff813085d1)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff81309683)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8130a794)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff81311515)
Location: include/linux/mm.h:1152
Inline: True
```
```
In fs/exec.c (ffffffff8131c40b)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8131eef8)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81321fb5)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81345755)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813508ca)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8135bad5)
Location: include/linux/mm.h:1152
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
In fs/block_dev.c (ffffffff8135ee23)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8136395b)
Location: include/linux/mm.h:1152
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
```
```
In fs/mpage.c (ffffffff8136559f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81376ff8)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81395ea3)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff81397d77)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff813a049d)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff813a3753)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff813ac259)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/proc/task_mmu.c (ffffffff813b8375)
Location: include/linux/mm.h:1152
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f39e1)
Location: include/linux/mm.h:1152
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
In fs/ext4/inode.c (ffffffff813ffd84)
Location: include/linux/mm.h:1152
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
In fs/ext4/mballoc.c (ffffffff8140c86a)
Location: include/linux/mm.h:1152
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
In fs/ext4/move_extent.c (ffffffff8140f47f)
Location: include/linux/mm.h:1152
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814186d4)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff81434dc3)
Location: include/linux/mm.h:1152
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8143bcb4)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff8143f9f7)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8144b5a2)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8144da74)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81451b7c)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81462d67)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81463220)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81470e19)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8147a740)
Location: include/linux/mm.h:1152
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
In fs/fuse/readdir.c (ffffffff81480609)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff814e4066)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8153f78f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff8154a9a2)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff8155ddfd)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff8155e0fc)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8155eb0f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8155f075)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8155fbaf)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81561b28)
Location: include/linux/mm.h:1152
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
In block/partitions/msdos.c (ffffffff815634b8)
Location: include/linux/mm.h:1152
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
In block/partitions/osf.c (ffffffff81563b6c)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81563df2)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815640b2)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8156431f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815646cd)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81565603)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8156584b)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710752)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81712a16)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8177446f)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8177c8c9)
Location: include/linux/mm.h:1152
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182cab6)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff818302df)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8188cfe7)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff81963ec0)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff819723ea)
Location: include/linux/mm.h:1152
Inline: True
```
```
In net/core/sock.c (ffffffff819e6307)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819f255a)
Location: include/linux/mm.h:1152
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
In net/core/dev.c (ffffffff819ff893)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a2cca0)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a35dcb)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3aaf3)
Location: include/linux/mm.h:1152
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
In net/core/skmsg.c (ffffffff81a3ced8)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81aaecdc)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81abc03b)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b085aa)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16e3d)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b22520)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81baae4c)
Location: include/linux/mm.h:1152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
```
**Symbols:**

```
ffffffff8100422e-ffffffff81004279: put_page (STB_LOCAL)
ffffffff812876b0-ffffffff812876fe: put_page (STB_LOCAL)
ffffffff8128b9f0-ffffffff8128ba3e: put_page (STB_LOCAL)
ffffffff812b5440-ffffffff812b548e: put_page (STB_LOCAL)
ffffffff812cb621-ffffffff812cb66c: put_page (STB_LOCAL)
ffffffff812fff40-ffffffff812fff8e: put_page (STB_LOCAL)
ffffffff8155e560-ffffffff8155e5ae: put_page (STB_LOCAL)
ffffffff81563c70-ffffffff81563cbe: put_page (STB_LOCAL)
ffffffff81563f00-ffffffff81563f4e: put_page (STB_LOCAL)
ffffffff8196fea4-ffffffff8196feef: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81bd1864)
Location: include/linux/mm.h:1194
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066087)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066e4e)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810a99f1)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8111462b)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811573d2)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff81233124)
Location: include/linux/mm.h:1194
Inline: True
```
```
In kernel/events/core.c (ffffffff8123baea)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812515aa)
Location: include/linux/mm.h:1194
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
In mm/filemap.c (ffffffff8125d83a)
Location: include/linux/mm.h:1194
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
In mm/page-writeback.c (ffffffff812642e1)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812672f2)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8126868d)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8126b77d)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_complete_page2
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81274cdc)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8127abeb)
Location: include/linux/mm.h:1194
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
In mm/compaction.c (ffffffff8128caea)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81291b96)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a012b)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:wp_page_shared
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_shared_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a1199)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a20d4)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b09bd)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c2c72)
Location: include/linux/mm.h:1194
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
In mm/swap_state.c (ffffffff812c5342)
Location: include/linux/mm.h:1194
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
In mm/swapfile.c (ffffffff812caf53)
Location: include/linux/mm.h:1194
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
In mm/zswap.c (ffffffff812cdb67)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812d7091)
Location: include/linux/mm.h:1194
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
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812d803c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff812e29fd)
Location: include/linux/mm.h:1194
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
In mm/memory_hotplug.c (ffffffff812ec338)
Location: include/linux/mm.h:1194
Inline: True
```
```
In mm/migrate.c (ffffffff812ee8d3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812fa081)
Location: include/linux/mm.h:1194
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
In mm/khugepaged.c (ffffffff812ff67c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff813077e3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130ebd9)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:__get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff81313070)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff81314396)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff81315493)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff813163cb)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff813278eb)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8132a428)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8132d575)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81351e93)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8135d89a)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff81366895)
Location: include/linux/mm.h:1194
Inline: True
```
```
In fs/buffer.c (ffffffff8136a085)
Location: include/linux/mm.h:1194
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
In fs/block_dev.c (ffffffff8136c603)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81370cb8)
Location: include/linux/mm.h:1194
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
In fs/mpage.c (ffffffff8137246f)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81384bff)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813a7bc3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/verify.c (ffffffff813a95f7)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff813b95f5)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813bd84c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff81406171)
Location: include/linux/mm.h:1194
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
In fs/ext4/inode.c (ffffffff8141259d)
Location: include/linux/mm.h:1194
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
In fs/ext4/mballoc.c (ffffffff8141fcda)
Location: include/linux/mm.h:1194
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
In fs/ext4/move_extent.c (ffffffff8142293b)
Location: include/linux/mm.h:1194
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c22f)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff8144d8a3)
Location: include/linux/mm.h:1194
Inline: True
```
```
In fs/ext4/verity.c (ffffffff81458026)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff8145bac7)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff81467c82)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146a034)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_read_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e037)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e807)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ea70)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148b6dc)
Location: include/linux/mm.h:1194
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
In fs/fuse/file.c (ffffffff81495444)
Location: include/linux/mm.h:1194
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
In fs/fuse/readdir.c (ffffffff8149bcec)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff8150148f)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff8155bfa5)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff815667bb)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81579c0c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81579d5c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8157a746)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8157ac35)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8157b6cf)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8157d5f8)
Location: include/linux/mm.h:1194
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
In block/partitions/msdos.c (ffffffff8157e5f5)
Location: include/linux/mm.h:1194
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
In block/partitions/osf.c (ffffffff8157ec9c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8157ef22)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8157f1d3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8157f45f)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8157f7ea)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815805a3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815807db)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d32f)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8172f7a6)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8178f1cf)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81795a19)
Location: include/linux/mm.h:1194
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183dbe7)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81840f56)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8189b220)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff8196a7b0)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff819772fa)
Location: include/linux/mm.h:1194
Inline: True
```
```
In net/core/sock.c (ffffffff819e5b17)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819f255a)
Location: include/linux/mm.h:1194
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
In net/core/dev.c (ffffffff819ff5f3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a2e259)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a37c9d)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3cdd1)
Location: include/linux/mm.h:1194
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
In net/core/skmsg.c (ffffffff81a3e391)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81ab8f3d)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ac777b)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16b0a)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81b250ad)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b30f20)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81bbb18c)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
```
**Symbols:**

```
ffffffff81bd1864-ffffffff81bd18ac: put_page (STB_LOCAL)
ffffffff81291500-ffffffff8129154b: put_page (STB_LOCAL)
ffffffff812969a0-ffffffff812969eb: put_page (STB_LOCAL)
ffffffff81be89c3-ffffffff81be8a0b: put_page (STB_LOCAL)
ffffffff8130c280-ffffffff8130c2cb: put_page (STB_LOCAL)
ffffffff8157a1a0-ffffffff8157a1eb: put_page (STB_LOCAL)
ffffffff8157eda0-ffffffff8157edeb: put_page (STB_LOCAL)
ffffffff8157f020-ffffffff8157f06b: put_page (STB_LOCAL)
ffffffff81c25ff2-ffffffff81c2603a: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81bc3874)
Location: include/linux/mm.h:1227
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:mount_block_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810664f2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810673fa)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810aaa22)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81114deb)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811587e6)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8124019a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81257b91)
Location: include/linux/mm.h:1227
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
In mm/filemap.c (ffffffff81260601)
Location: include/linux/mm.h:1227
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
In mm/page-writeback.c (ffffffff81269ec1)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8126ba69)
Location: include/linux/mm.h:1227
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
In mm/swap.c (ffffffff8126e01d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8127030d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81279fdc)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8127fd64)
Location: include/linux/mm.h:1227
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
In mm/compaction.c (ffffffff81291d63)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81297486)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812a5a68)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812a6db3)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812a7964)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812b5fef)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memory_hotplug.c (ffffffff812c6a57)
Location: include/linux/mm.h:1227
Inline: True
```
```
In mm/madvise.c (ffffffff812c9aee)
Location: include/linux/mm.h:1227
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
In mm/swap_state.c (ffffffff812cbff2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812d1a31)
Location: include/linux/mm.h:1227
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
In mm/zswap.c (ffffffff812d4e8e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812de688)
Location: include/linux/mm.h:1227
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
Direct callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812e0900)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812ea18d)
Location: include/linux/mm.h:1227
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
In mm/migrate.c (ffffffff812f4a63)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81300e2d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
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
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8130631e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff8130df64)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81315130)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_any_page
```
```
In mm/zsmalloc.c (ffffffff813192a6)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff8131b1bd)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffffffff8131bb63)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff8131c4a1)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff8132d765)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813303c8)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81332f15)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81358bb7)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8136432e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff8136d145)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/buffer.c (ffffffff81371336)
Location: include/linux/mm.h:1227
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
In fs/block_dev.c (ffffffff81372f33)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8137759e)
Location: include/linux/mm.h:1227
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
In fs/mpage.c (ffffffff8137854f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff8138b6ec)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813aec25)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff813b06e4)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/verity/verify.c (ffffffff813b0b37)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff813c0760)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff813c4994)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead_actor
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff8140c650)
Location: include/linux/mm.h:1227
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
In fs/ext4/inode.c (ffffffff81418a0d)
Location: include/linux/mm.h:1227
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
In fs/ext4/mballoc.c (ffffffff81420867)
Location: include/linux/mm.h:1227
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
Direct callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff8142914a)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81432f0f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814533a5)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/ext4/verity.c (ffffffff8145d9de)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff81461407)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff8146d28a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146f7ba)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81473478)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff81484399)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff814845f5)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814906ae)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8149a4a4)
Location: include/linux/mm.h:1227
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
In fs/fuse/readdir.c (ffffffff814a0e06)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81507f6f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff815639ae)
Location: include/linux/mm.h:1227
Inline: True
```
```
In block/blk-map.c (ffffffff8156ecf9)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff8158193f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff81581a8c)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81582476)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff81582965)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815833d6)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff81585188)
Location: include/linux/mm.h:1227
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
In block/partitions/msdos.c (ffffffff8158617c)
Location: include/linux/mm.h:1227
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
In block/partitions/osf.c (ffffffff815867fc)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81586a7e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81586d39)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81586f9f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81587329)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff81588113)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8158834b)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff815eff29)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171109c)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81713809)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81771fbc)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817786d9)
Location: include/linux/mm.h:1227
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820d77)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff81824146)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8187da7d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff8194e5c0)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff8195ba0a)
Location: include/linux/mm.h:1227
Inline: True
```
```
In net/core/sock.c (ffffffff819cbc27)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819d8787)
Location: include/linux/mm.h:1227
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
In net/core/dev.c (ffffffff819e5d64)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81a14f10)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81a1ee2e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a23b91)
Location: include/linux/mm.h:1227
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
In net/core/skmsg.c (ffffffff81a4dab9)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/ipv4/tcp.c (ffffffff81aa41f0)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ab278b)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04828)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12ccd)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81b1ec4e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81baa7cc)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_clear_xmit
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff81bc3874-ffffffff81bc38bc: put_page (STB_LOCAL)
ffffffff8129c540-ffffffff8129c58b: put_page (STB_LOCAL)
ffffffff81bda9df-ffffffff81bdaa27: put_page (STB_LOCAL)
ffffffff812f9bf0-ffffffff812f9c3b: put_page (STB_LOCAL)
ffffffff813129e0-ffffffff81312a2b: put_page (STB_LOCAL)
ffffffff8141bdb0-ffffffff8141bdfb: put_page (STB_LOCAL)
ffffffff8148e080-ffffffff8148e0cb: put_page (STB_LOCAL)
ffffffff81581ed0-ffffffff81581f1b: put_page (STB_LOCAL)
ffffffff81586900-ffffffff8158694b: put_page (STB_LOCAL)
ffffffff81586b80-ffffffff81586bcb: put_page (STB_LOCAL)
ffffffff81c18177-ffffffff81c181bf: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81c948da)
Location: include/linux/mm.h:1231
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070614)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071788)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810bc549)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff811354a3)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8117d6f3)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8127ac07)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81291249)
Location: include/linux/mm.h:1231
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
In mm/filemap.c (ffffffff8129cff2)
Location: include/linux/mm.h:1231
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
In mm/page-writeback.c (ffffffff812a6b54)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812a8739)
Location: include/linux/mm.h:1231
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
In mm/swap.c (ffffffff812aaf6d)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff812ad5b2)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b7ffd)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff812be074)
Location: include/linux/mm.h:1231
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
In mm/compaction.c (ffffffff812d141b)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7e36)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812dd0d0)
Location: include/linux/mm.h:1231
Inline: False
Direct callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812e828f)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/mlock.c (ffffffff812e8f84)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff812f9a93)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memory_hotplug.c (ffffffff8130b503)
Location: include/linux/mm.h:1231
Inline: True
```
```
In mm/madvise.c (ffffffff8130eb0e)
Location: include/linux/mm.h:1231
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
In mm/swap_state.c (ffffffff813111cc)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81317195)
Location: include/linux/mm.h:1231
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
In mm/zswap.c (ffffffff8131a498)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff813259b6)
Location: include/linux/mm.h:1231
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
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:alloc_surplus_huge_page
```
```
In mm/mempolicy.c (ffffffff81326dc6)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff813320af)
Location: include/linux/mm.h:1231
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
In mm/migrate.c (ffffffff8133f203)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_unmap
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
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134aaa7)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
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
```
```
In mm/khugepaged.c (ffffffff8135016e)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff81358dc3)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff813611c9)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:page_handle_poison
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:get_any_page
```
```
In mm/zsmalloc.c (ffffffff81365991)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813667a5)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813683bb)
Location: include/linux/mm.h:1231
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
In mm/page_idle.c (ffffffff81368e23)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memremap.c (ffffffff813697a1)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/exec.c (ffffffff8137af95)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff8137db88)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff813806a5)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff813a72a7)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff813b2b45)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/remap_range.c (ffffffff813bbe25)
Location: include/linux/mm.h:1231
Inline: True
```
```
In fs/buffer.c (ffffffff813bfc47)
Location: include/linux/mm.h:1231
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
In fs/direct-io.c (ffffffff813c3ba3)
Location: include/linux/mm.h:1231
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
In fs/mpage.c (ffffffff813c4e2f)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff813d8c9f)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff813fe7c5)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/verity/read_metadata.c (ffffffff814002d1)
Location: include/linux/mm.h:1231
Inline: True
```
```
In fs/verity/verify.c (ffffffff81400737)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff814105cc)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/iomap/buffered-io.c (ffffffff8141414a)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff8145f0cc)
Location: include/linux/mm.h:1231
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
In fs/ext4/inode.c (ffffffff8146bc10)
Location: include/linux/mm.h:1231
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
In fs/ext4/mballoc.c (ffffffff81473c2a)
Location: include/linux/mm.h:1231
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
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff8147cf46)
Location: include/linux/mm.h:1231
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486864)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff814a7385)
Location: include/linux/mm.h:1231
Inline: True
```
```
In fs/ext4/verity.c (ffffffff814b2e9e)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffff814b68f7)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/squashfs/file.c (ffffffff814c3b16)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814c6224)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca06d)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff814dba19)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbc75)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e813e)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814f1f14)
Location: include/linux/mm.h:1231
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
In fs/fuse/readdir.c (ffffffff814f8dfa)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff815651ad)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff815c5363)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff815c8b40)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff815d3335)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff815e6d40)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff815e6e86)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff815e77d3)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff815e7c9e)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff815e8cc6)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff815eaae8)
Location: include/linux/mm.h:1231
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
In block/partitions/msdos.c (ffffffff815ebba5)
Location: include/linux/mm.h:1231
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
In block/partitions/osf.c (ffffffff815ec34c)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff815ec5bd)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff815ec871)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff815ecb1f)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff815ece98)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815eddb3)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff815edfeb)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff8165d1c9)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178dbb6)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff817910c2)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817f7d5c)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff817fe589)
Location: include/linux/mm.h:1231
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab6cc)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff818af986)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8190f17c)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
```
```
In drivers/md/md.c (ffffffff819f39c6)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81a0120a)
Location: include/linux/mm.h:1231
Inline: True
```
```
In net/core/sock.c (ffffffff81a7b287)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81a886bb)
Location: include/linux/mm.h:1231
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
In net/core/dev.c (ffffffff81a97f78)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81ac8823)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81ad2ece)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad821d)
Location: include/linux/mm.h:1231
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
In net/core/skmsg.c (ffffffff81b06351)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_trim
```
```
In net/ipv4/tcp.c (ffffffff81b603fb)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f677)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6b89)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6bcb)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81be38bc)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81c7e64d)
Location: include/linux/mm.h:1231
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff81c948da-ffffffff81c9491f: put_page (STB_LOCAL)
ffffffff812dd0d0-ffffffff812dd118: put_page (STB_LOCAL)
ffffffff8131bb70-ffffffff8131bbb8: put_page (STB_LOCAL)
ffffffff813510a0-ffffffff813510e8: put_page (STB_LOCAL)
ffffffff8135e410-ffffffff8135e458: put_page (STB_LOCAL)
ffffffff8146f190-ffffffff8146f1d8: put_page (STB_LOCAL)
ffffffff814e5af0-ffffffff814e5b38: put_page (STB_LOCAL)
ffffffff815e7230-ffffffff815e7278: put_page (STB_LOCAL)
ffffffff815ec440-ffffffff815ec488: put_page (STB_LOCAL)
ffffffff815ec690-ffffffff815ec6d8: put_page (STB_LOCAL)
ffffffff81d27573-ffffffff81d275b8: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81e43a6d)
Location: include/linux/mm.h:1227
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db6e)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f7f9)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810d30dd)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff811579a0)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811b2776)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff812cdbea)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e67ed)
Location: include/linux/mm.h:1227
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
In mm/filemap.c (ffffffff812f3506)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/readahead.c (ffffffff81301990)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/truncate.c (ffffffff8130804f)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/vmscan.c (ffffffff8130d99a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/shmem.c (ffffffff8131992f)
Location: include/linux/mm.h:1227
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
In mm/compaction.c (ffffffff81330eb2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81337960)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff813480ec)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/mincore.c (ffffffff81349601)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:__mincore_unmapped_range
```
```
In mm/memory_hotplug.c (ffffffff81374252)
Location: include/linux/mm.h:1227
Inline: True
```
```
In mm/madvise.c (ffffffff81376afe)
Location: include/linux/mm.h:1227
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
In mm/swap_state.c (ffffffff8137c128)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813828d3)
Location: include/linux/mm.h:1227
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
In mm/zswap.c (ffffffff81385962)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81394610)
Location: include/linux/mm.h:1227
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
Direct callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_surplus_huge_page
```
```
In mm/mempolicy.c (ffffffff81396e4d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff813a3188)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
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
In mm/migrate.c (ffffffff813b6010)
Location: include/linux/mm.h:1227
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
In mm/migrate_device.c (ffffffff813b6449)
Location: include/linux/mm.h:1227
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
In mm/huge_memory.c (ffffffff813c1a56)
Location: include/linux/mm.h:1227
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
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c832a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/memcontrol.c (ffffffff813d2ff0)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd3fe)
Location: include/linux/mm.h:1227
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
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
```
```
In mm/zsmalloc.c (ffffffff813e1e58)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff813e3ace)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e5a3d)
Location: include/linux/mm.h:1227
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
In mm/page_idle.c (ffffffff813e6796)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/exec.c (ffffffff813fb262)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fe3e0)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff81400695)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff8142c7be)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81437bb6)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff814468df)
Location: include/linux/mm.h:1227
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
In fs/direct-io.c (ffffffff8144a771)
Location: include/linux/mm.h:1227
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
In fs/mpage.c (ffffffff8144bc80)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/aio.c (ffffffff81464764)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff814722df)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff81474063)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/verity/verify.c (ffffffff81474757)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff814860bc)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/inline.c (ffffffff814ddb1f)
Location: include/linux/mm.h:1227
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff814e3f37)
Location: include/linux/mm.h:1227
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
In fs/ext4/mballoc.c (ffffffff814f5410)
Location: include/linux/mm.h:1227
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
In fs/ext4/move_extent.c (ffffffff814ff79b)
Location: include/linux/mm.h:1227
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a163)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8153c63a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff8154e758)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511e2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff81555d80)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff815695eb)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff815698ec)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81577115)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8157f837)
Location: include/linux/mm.h:1227
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
In fs/fuse/readdir.c (ffffffff8158944a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816009be)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81670462)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff81673bab)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8167f093)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/partitions/core.c (ffffffff81695f22)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/core.c:read_part_sector
```
```
In block/partitions/amiga.c (ffffffff816960d1)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff81696c07)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8169724c)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:read_lba
```
```
In block/partitions/mac.c (ffffffff8169845a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8169a632)
Location: include/linux/mm.h:1227
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
In block/partitions/msdos.c (ffffffff8169bb93)
Location: include/linux/mm.h:1227
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
In block/partitions/osf.c (ffffffff8169c57a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff8169c8ff)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
Direct callers:
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff8169cbf4)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
Direct callers:
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff8169cfbb)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff8169d3c3)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff8169e3a2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff8169e6f5)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In lib/buildid.c (ffffffff81776630)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c636c)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff818c8d67)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81936ad4)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff8193db3e)
Location: include/linux/mm.h:1227
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e60)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81a63e10)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81b5d65d)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81b68cec)
Location: include/linux/mm.h:1227
Inline: True
```
```
In net/core/sock.c (ffffffff81bed232)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81bfddbb)
Location: include/linux/mm.h:1227
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
In net/core/filter.c (ffffffff81c44d86)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81c51806)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c53946)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81c58ffe)
Location: include/linux/mm.h:1227
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
In net/core/skmsg.c (ffffffff81c8c0fe)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81ceed05)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81cfed3a)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c358)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7a2)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81d7b310)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81e1d73b)
Location: include/linux/mm.h:1227
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
**Symbols:**

```
ffffffff81e43a6d-ffffffff81e43add: put_page (STB_LOCAL)
ffffffff8133cf00-ffffffff8133cf6d: put_page (STB_LOCAL)
ffffffff8138a050-ffffffff8138a0ed: put_page (STB_LOCAL)
ffffffff813b9570-ffffffff813b960d: put_page (STB_LOCAL)
ffffffff813d91d0-ffffffff813d926d: put_page (STB_LOCAL)
ffffffff814dbf60-ffffffff814dbffd: put_page (STB_LOCAL)
ffffffff815752c0-ffffffff8157535d: put_page (STB_LOCAL)
ffffffff81696590-ffffffff8169662d: put_page (STB_LOCAL)
ffffffff8169c700-ffffffff8169c79d: put_page (STB_LOCAL)
ffffffff8169ca60-ffffffff8169cafd: put_page (STB_LOCAL)
ffffffff81ef38a5-ffffffff81ef3915: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83e62318)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f0fc)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810918e5)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810f1c0b)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8118888c)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff811f3616)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff81339173)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813502d1)
Location: include/linux/mm.h:1315
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
In mm/filemap.c (ffffffff8135d856)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/readahead.c (ffffffff8136c186)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
```
```
In mm/truncate.c (ffffffff81371fff)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/shmem.c (ffffffff8138cc39)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/compaction.c (ffffffff813a76e3)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af000)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813c058d)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/memory_hotplug.c (ffffffff813f1d25)
Location: include/linux/mm.h:1315
Inline: True
```
```
In mm/madvise.c (ffffffff813f499c)
Location: include/linux/mm.h:1315
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
In mm/swap_state.c (ffffffff813f98c8)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff813fc87f)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff8140369f)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8141308a)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
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
```
```
In mm/mempolicy.c (ffffffff814169be)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81422e01)
Location: include/linux/mm.h:1315
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
In mm/migrate.c (ffffffff81436164)
Location: include/linux/mm.h:1315
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
In mm/migrate_device.c (ffffffff81438891)
Location: include/linux/mm.h:1315
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
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443b44)
Location: include/linux/mm.h:1315
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
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81449798)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8145880a)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8146411d)
Location: include/linux/mm.h:1315
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
Direct callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8146943b)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff8146b4ab)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146d5e6)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff8146e296)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/exec.c (ffffffff81485323)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff81488060)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff8148a865)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814ba02e)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814c5eb4)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff814d59eb)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/direct-io.c (ffffffff814d8e73)
Location: include/linux/mm.h:1315
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
In fs/aio.c (ffffffff814f2362)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/enable.c (ffffffff81503dcd)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree_level
```
```
In fs/verity/read_metadata.c (ffffffff815062b7)
Location: include/linux/mm.h:1315
Inline: True
```
```
In fs/verity/verify.c (ffffffff81506d4c)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/coredump.c (ffffffff8151990b)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/inline.c (ffffffff81576b64)
Location: include/linux/mm.h:1315
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8157d53d)
Location: include/linux/mm.h:1315
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
In fs/ext4/mballoc.c (ffffffff81590e30)
Location: include/linux/mm.h:1315
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
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/move_extent.c (ffffffff81599f47)
Location: include/linux/mm.h:1315
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4c88)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff815dad25)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/squashfs/file.c (ffffffff815eedd5)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f234e)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7478)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d1cb)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d51d)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8161b7f5)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81625517)
Location: include/linux/mm.h:1315
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
In fs/fuse/readdir.c (ffffffff8162f6f9)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816b1925)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff8172b802)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In block/bio.c (ffffffff8172f6ae)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
```
```
In block/blk-map.c (ffffffff8173c191)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In drivers/pci/p2pdma.c (ffffffff8191beda)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16c9b)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a1a0e7)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a96974)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81a9ea6e)
Location: include/linux/mm.h:1315
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7342d)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81bf2ff6)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/md/md.c (ffffffff81cf75a9)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d0480c)
Location: include/linux/mm.h:1315
Inline: True
```
```
In net/core/sock.c (ffffffff81d994f2)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81da4ff6)
Location: include/linux/mm.h:1315
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
In net/core/filter.c (ffffffff81dff34c)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e06cc4)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e090fa)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e0ef5e)
Location: include/linux/mm.h:1315
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
In net/core/skmsg.c (ffffffff81e47350)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81eb1f81)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3b86)
Location: include/linux/mm.h:1315
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f264ea)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f38d72)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81f4837f)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff81ff4ebd)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8201f07d)
Location: include/linux/mm.h:1315
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813b4ea0-ffffffff813b4eff: put_page (STB_LOCAL)
ffffffff81407430-ffffffff814074cd: put_page (STB_LOCAL)
ffffffff8143bb50-ffffffff8143bbed: put_page (STB_LOCAL)
ffffffff8145f230-ffffffff8145f2cd: put_page (STB_LOCAL)
ffffffff81574ef0-ffffffff81574f8d: put_page (STB_LOCAL)
ffffffff8158b2f0-ffffffff8158b38d: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83682825)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091ffc)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094822)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff810fdb8e)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81199a4c)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex/core.c (ffffffff81207dc8)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/core.c (ffffffff8136a78f)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813814b6)
Location: include/linux/mm.h:1499
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
In mm/truncate.c (ffffffff813a41a1)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/gup.c (ffffffff813e35df)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff813f52e3)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
Direct callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
```
```
In mm/memory_hotplug.c (ffffffff814258d2)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/madvise.c (ffffffff81427586)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c841)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8142fc88)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:unuse_pte
```
```
In mm/zswap.c (ffffffff814375b9)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81440d6a)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/mempolicy.c (ffffffff81449ed9)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81457f79)
Location: include/linux/mm.h:1499
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
In mm/migrate.c (ffffffff8146bd37)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146e591)
Location: include/linux/mm.h:1499
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
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81479092)
Location: include/linux/mm.h:1499
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
In mm/khugepaged.c (ffffffff8147f7ae)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8148e3d7)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
Direct callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81499bd0)
Location: include/linux/mm.h:1499
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
In mm/zsmalloc.c (ffffffff8149e3ca)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/secretmem.c (ffffffff814a028d)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/exec.c (ffffffff814ba391)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814bcf4d)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814c0a35)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff814eefab)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff814fb394)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8150a933)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff81528faa)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff8153d5ed)
Location: include/linux/mm.h:1499
Inline: True
```
```
In fs/verity/verify.c (ffffffff8153ded8)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815511ff)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/mballoc.c (ffffffff815c636d)
Location: include/linux/mm.h:1499
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
In fs/squashfs/block.c (ffffffff816241a0)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff81626dc1)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a43e)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8162fae2)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8164508b)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff816453dc)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81653965)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8165d887)
Location: include/linux/mm.h:1499
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
In fs/fuse/readdir.c (ffffffff8166796c)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff816ea328)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff81767682)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In drivers/pci/p2pdma.c (ffffffff8195f4ed)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fd2b)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81a62c87)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae2185)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81aea3e6)
Location: include/linux/mm.h:1499
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d60)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81c4a24d)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81c541be)
Location: include/linux/mm.h:1499
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
In drivers/md/md.c (ffffffff81d5eea5)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:export_rdev
  - drivers/md/md.c:export_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81d6d8cc)
Location: include/linux/mm.h:1499
Inline: True
```
```
In net/core/sock.c (ffffffff81e07812)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81e1eaac)
Location: include/linux/mm.h:1499
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
In net/core/filter.c (ffffffff81e70e1c)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81e79604)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7b765)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81e8271e)
Location: include/linux/mm.h:1499
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
In net/core/skmsg.c (ffffffff81ea2db8)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81f1062f)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81f22d42)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86173)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff81f98a5e)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff81fa7f30)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff820716d9)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff8209f090)
Location: include/linux/mm.h:1499
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813ea470-ffffffff813ea50d: put_page (STB_LOCAL)
ffffffff814878d0-ffffffff8148796d: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff838b18c5)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root_generic
  - init/do_mounts.c:do_mount_root
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109936c)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bd02)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In kernel/exit.c (ffffffff81106941)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff811a8aac)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/events/core.c (ffffffff8139311f)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813aa865)
Location: include/linux/mm.h:1553
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
In mm/truncate.c (ffffffff813cdcf1)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
```
```
In mm/gup.c (ffffffff8140ddff)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/gup.c:undo_dev_pagemap
```
```
In mm/memory.c (ffffffff81415b0f)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
Direct callers:
  - mm/memory.c:do_swap_page
```
```
In mm/memory_hotplug.c (ffffffff81452b24)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swap_state.c (ffffffff8146564e)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81469771)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In mm/hugetlb.c (ffffffff8147ae9a)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/mempolicy.c (ffffffff8148396d)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81491dc5)
Location: include/linux/mm.h:1553
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
In mm/migrate.c (ffffffff81496f05)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In mm/migrate_device.c (ffffffff8149ef1e)
Location: include/linux/mm.h:1553
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
In mm/huge_memory.c (ffffffff814a1b61)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/khugepaged.c (ffffffff814ad762)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814bdc44)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
Direct callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c93c0)
Location: include/linux/mm.h:1553
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
In mm/zsmalloc.c (ffffffff814cd4fb)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:__free_zspage
```
```
In fs/exec.c (ffffffff814ec911)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff814ef3ed)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff814f3085)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/splice.c (ffffffff81530086)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8153f483)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
```
```
In fs/aio.c (ffffffff8155de8a)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/aio.c:aio_free_ring
```
```
In fs/verity/read_metadata.c (ffffffff81572a4d)
Location: include/linux/mm.h:1553
Inline: True
```
```
In fs/verity/verify.c (ffffffff81573475)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
  - fs/verity/verify.c:verify_data_block
```
```
In fs/coredump.c (ffffffff815870e3)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/coredump.c:dump_user_range
```
```
In fs/ext4/mballoc.c (ffffffff81601cbb)
Location: include/linux/mm.h:1553
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
In fs/squashfs/block.c (ffffffff8165d240)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_bio_read
```
```
In fs/squashfs/file.c (ffffffff8165ff22)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_readahead
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81663768)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e5bb)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8167e8fd)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8168cf75)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff816975c7)
Location: include/linux/mm.h:1553
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
In fs/fuse/readdir.c (ffffffff816a1cb0)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81727038)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/fops.c (ffffffff817a9472)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - block/fops.c:blkdev_write_end
```
```
In drivers/pci/p2pdma.c (ffffffff819a8b4d)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab253b)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff81ab52b7)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b35575)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/char/agp/generic.c (ffffffff81b3d876)
Location: include/linux/mm.h:1553
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b8cf)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/net/tun.c (ffffffff81cffbd9)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
```
```
In drivers/net/virtio_net.c (ffffffff81d078c2)
Location: include/linux/mm.h:1553
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
In drivers/md/md.c (ffffffff81e16115)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffffffff81e24d0c)
Location: include/linux/mm.h:1553
Inline: True
```
```
In net/core/sock.c (ffffffff81ec4252)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/sock.c:skb_page_frag_refill
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff81edc10c)
Location: include/linux/mm.h:1553
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
In net/core/filter.c (ffffffff81f304f3)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81f3969e)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3b9f5)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
```
```
In net/core/page_pool.c (ffffffff81f436ad)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/skmsg.c (ffffffff81f650e8)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81fd481e)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7bd2)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d753)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/xfrm_state.c (ffffffff82065dce)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/espintcp.c (ffffffff820751f0)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
```
In net/mptcp/protocol.c (ffffffff82145859)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - net/mptcp/protocol.c:dfrag_clear
```
```
In lib/buildid.c (ffffffff82177090)
Location: include/linux/mm.h:1553
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff81415f40-ffffffff81415fd6: put_page (STB_LOCAL)
ffffffff814b7840-ffffffff814b78d6: put_page (STB_LOCAL)
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
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff800011431850)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In virt/kvm/kvm_main.c (ffff8000100bbf68)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca920)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/exit.c (ffff8000100fd858)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/futex.c (ffff8000101b7bc4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffff80001028bc00)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff80001029f544)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffff8000102a59bc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b16a4)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffff8000102bd24c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffff8000102bf1b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffff8000102c0ce4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffff8000102c4078)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cb508)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffff8000102d5994)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffff8000102f127c)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffff8000102fb9f8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffff8000102fcce8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffff8000102fe1b4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff800010309eac)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffff8000103123dc)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffff80001031e6d8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/swap_state.c (ffff800010322394)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010327a30)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffff80001032c5d0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff8000103361bc)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffff800010339b3c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffff80001034177c)
Location: include/linux/mm.h:1036
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffff8000103530e8)
Location: include/linux/mm.h:1036
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
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359c14)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
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
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f804)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010368bb8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff800010370630)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffff800010375cf0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffff800010378410)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff800010379338)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffff800010379d54)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffff80001038044c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/exec.c (ffff80001038c378)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffff80001038fcac)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffff800010393340)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffff8000103c0a48)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffff8000103ce460)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffff8000103dcff8)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffff8000103e0ab8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffff8000103e4f4c)
Location: include/linux/mm.h:1036
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
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e6ee0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffff8000103fd038)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffff80001040115c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffff800010411108)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffff800010413390)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffff800010420f44)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff8000104247f4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffff80001042bbec)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffff80001043a384)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffff80001047b2fc)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffff800010488fb0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/mballoc.c (ffff8000104924e0)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffff80001049a7a4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffff8000104a4de0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffff8000104c0f44)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffff8000104c8328)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffff8000104cf400)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffff8000104dbc9c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffff8000104de12c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffff8000104e24cc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffff8000104f6258)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffff8000104f66d4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff800010504bc0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffff80001050e628)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (ffff8000105154b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffff80001058029c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffff8000105dd184)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffff8000105fd0ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffff8000105ff510)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff800010600080)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff8000106004f0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff8000106010b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff8000106030ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
```
In block/partitions/msdos.c (ffff800010604970)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffff8000106051e4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff8000106054a8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605810)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605ab0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff80001060600c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffff800010606c40)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010606ef0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b228)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffff80001082e22c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffff8000108b3818)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cbe8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffff800010970d0c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffff8000109e18d4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2b50)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/md/md.c (ffff800010ae9b0c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
Direct callers:
  - drivers/md/md.c:read_rdev
```
```
In drivers/md/md-bitmap.c (ffff800010af6c9c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffff800010baca04)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffff800010bb9dbc)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffff800010bced10)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffff800010bfdbf4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffff800010c06d40)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffff800010c0ca54)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffff800010c0e770)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffff800010c7617c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffff800010c81f78)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd360c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffff800010ce35d8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffff8000102f3fd8-ffff8000102f402c: put_page (STB_LOCAL)
ffff80001031d740-ffff80001031d794: put_page (STB_LOCAL)
ffff80001032e910-ffff80001032e964: put_page (STB_LOCAL)
ffff80001036e298-ffff80001036e2ec: put_page (STB_LOCAL)
ffff800010478ea8-ffff800010478efc: put_page (STB_LOCAL)
ffff80001047dd18-ffff80001047dd6c: put_page (STB_LOCAL)
ffff8000105ff9a8-ffff8000105ff9fc: put_page (STB_LOCAL)
ffff8000109e2bd8-ffff8000109e2c2c: put_page (STB_LOCAL)
ffff800010ae6590-ffff800010ae65e4: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c1501874)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/mm/fault-armv.c (c1507e80)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In kernel/exit.c (c035aa78)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (c03c0aec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (c040197c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (c04bb25c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c04cf50c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (c04d74bc)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (c04de174)
Location: include/linux/mm.h:1036
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
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c04e9790)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c04eaed4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c04eca20)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c04eeb08)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f5520)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (c04fdb34)
Location: include/linux/mm.h:1036
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
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (c0515660)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c051c088)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
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
In mm/mincore.c (c051c404)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c051cdf4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c05266e8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (c052d26c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (c05385cc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053aa44)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053ef60)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c05428e8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (c0546620)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (c0552e90)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (c055a218)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (c0561f94)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c0563978)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564a04)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c0564f84)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (c056b698)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/exec.c (c0574b18)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (c0576ab4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c057a260)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c059df68)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (c05a9bbc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (c05b64dc)
Location: include/linux/mm.h:1036
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
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (c05b85bc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (c05bcf10)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (c05bebb4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (c05cf880)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c05d2eec)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (c05dd74c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c05df6e0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c05e91f0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/binfmt_elf_fdpic.c (c05ea314)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
```
In fs/iomap/buffered-io.c (c05f5004)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (c0600cb0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/ext4/inline.c (c063cb9c)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (c064b530)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (c0653880)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (c065c11c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (c0666658)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0684bc0)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (c068bd80)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (c06920ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c069d3a8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd60)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c06b3bd4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c06b4088)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c06c1230)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c06c9dd8)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (c06d040c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0732788)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (c078a5f0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (c07a78f8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c07aa7d4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07ab3b8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07ab7dc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c07ac4a0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae6a8)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (c07afc14)
Location: include/linux/mm.h:1036
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
In block/partitions/osf.c (c07b03ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b05cc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b08d8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0b30)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b0e18)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c07b1f80)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b234c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (c09476b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (c09ad670)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (c0a4210c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c0a457d8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (c0ac6b18)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md.c (c0bccde4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (c0bd9300)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (c0ccaa04)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c0cd67c0)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (c0ce4a80)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (c0d1a038)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c0d2006c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c0d251a8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d2746c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (c0d848b8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c0d90b40)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (c0ddd3bc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (c0debb6c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
c063a9b4-c063aa00: put_page (STB_LOCAL)
c07aac60-c07aacac: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000001344c1c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0eb4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In kernel/exit.c (c0000000001447c0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/futex.c (c00000000021d080)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (c000000000337c40)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000350874)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (c00000000035bca0)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (c000000000367510)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (c000000000375dc0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c00000000037806c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c00000000037bf80)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c00000000037e84c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c0000000003884fc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (c0000000003958b0)
Location: include/linux/mm.h:1036
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
Location: include/linux/mm.h:1036
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
In mm/memory.c (c0000000003c6d9c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (c0000000003c7c58)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c0000000003c98ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003d9860)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (c0000000003e3164)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (c0000000003f28d0)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swap_state.c (c0000000003f7e98)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fe8f8)
Location: include/linux/mm.h:1036
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
In mm/zswap.c (c000000000404040)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (c0000000004109cc)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (c0000000004142ec)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (c00000000041ed04)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (c00000000042e294)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c0000000004368ac)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (c000000000444248)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (c00000000044b178)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c000000000457010)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c000000000461dc0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (c0000000004686e0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c00000000046aebc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c928)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046d108)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (c00000000046dc3c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (c0000000004772c0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/exec.c (c000000000484cdc)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (c000000000487958)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c00000000048c824)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (c0000000004bf19c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (c0000000004d17a0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (c0000000004de964)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (c0000000004e4fb0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (c0000000004eb308)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (c0000000004ed3e4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (c000000000504e98)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c00000000050ab7c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (c00000000051ec5c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c0000000005211d4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c00000000052fcc8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338e8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (c00000000053ce54)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (c00000000054e268)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (c00000000059e5e8)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (c0000000005afd8c)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (c0000000005baa0c)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (c0000000005c4f70)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (c0000000005d1ee0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f786c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (c000000000600910)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (c000000000608194)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c000000000616e54)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619e10)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (c00000000061f540)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (c000000000637128)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c000000000637658)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c000000000649e00)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c00000000065574c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (c00000000065debc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0000000006edbd0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (c00000000076e790)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (c000000000796790)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c0000000007996b4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a634)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079acb4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bc78)
Location: include/linux/mm.h:1036
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
In block/partitions/ldm.c (c00000000079e8fc)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (c0000000007a0718)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (c0000000007a0ec4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a12dc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a172c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1aa4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1e5c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a3338)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a36fc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d67e0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (c00000000094bc78)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (c000000000955cd0)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (c000000000a253d0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c000000000a29f2c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (c000000000aa3688)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2cb8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
```
```
In drivers/md/md.c (c000000000bd734c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (c000000000be4e1c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (c000000000c806c8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c000000000c9255c)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (c000000000ca50b0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (c000000000ce9878)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c000000000cf146c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c000000000cf839c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c000000000cfb4d8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (c000000000d7dc24)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c000000000d8cd68)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (c000000000df1c20)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (c000000000e056b8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
c0000000003f1610-c0000000003f16c8: put_page (STB_LOCAL)
c000000000405d50-c000000000405e08: put_page (STB_LOCAL)
c00000000045dd20-c00000000045ddd8: put_page (STB_LOCAL)
c00000000059b7a0-c00000000059b858: put_page (STB_LOCAL)
c000000000799d10-c000000000799dc8: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffe00000150e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffe0000c603e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/futex.c (ffffffe00013c8a4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf6ee)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffe0001cef2e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In mm/filemap.c (ffffffe0001d71be)
Location: include/linux/mm.h:1036
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
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffe0001dffe4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffe0001e15e8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffe0001e31ca)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffe0001e4bc4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffe0001ea318)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffe0001f13fc)
Location: include/linux/mm.h:1036
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
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/gup.c (ffffffe00020539c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffe00020b038)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffe00020b932)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffe00020c260)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffe000213e20)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffe00021999c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffe0002215ae)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe000223364)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000227a28)
Location: include/linux/mm.h:1036
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
In mm/zswap.c (ffffffe00022b1a8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffe00023224a)
Location: include/linux/mm.h:1036
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/ksm.c (ffffffe000234ef4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffe00023ff92)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffe00024686c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffe00024e468)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffe00024fcfc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffe000250bbc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000251046)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/read_write.c (ffffffe000255d16)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/exec.c (ffffffe00025dcea)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (ffffffe00025f9f8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffe000262166)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffe000281046)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffe00028b428)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffe00029517e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffe000296a3a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffe00029ab18)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffe00029c004)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffe0002aaf86)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffe0002ad4dc)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffe0002b955a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffe0002bb054)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffe0002c191c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffe0002c9342)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffe0002d3478)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffe000305848)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffe0003108ba)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffe00031723e)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffe00031df2c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffe000325e22)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffe00033c606)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffe000341e20)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/commit.c (ffffffe000346cd0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffe000350942)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffe000352b28)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffe000355fb4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffe00036506a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffe000365418)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffe0003716d0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffe000379238)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/readdir.c (ffffffe00037ee7c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffe0003d0f18)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffe00042035c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffe000438ce8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffe00043aa64)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffe00043b88c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffe00043bca2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffe00043c5d2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffe00043e6da)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffe00043f90c)
Location: include/linux/mm.h:1036
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
In block/partitions/osf.c (ffffffe00043fdce)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffe00043ffdc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffe0004402c0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffe0004404ca)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffe000440642)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffe000441b24)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffe000441cb0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fdac)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffe000564f62)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d7414)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffe0005da246)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffe00062b35a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffe0006de1fe)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9c2c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffe00073e940)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffe000749268)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffe0007551a6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffe00077d312)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffe000785188)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffe000789bf6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffe00078bac6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffe0007d938a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3a1c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffe0008244bc)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffe00083109e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffe000303d12-ffffffe000303d4c: put_page (STB_LOCAL)
ffffffe00043af6c-ffffffe00043afa6: put_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8288b720)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a02f6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff81105d66)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81142d61)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811fba8c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120db51)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8121508c)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (ffffffff8121c413)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffffffff81226979)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81228236)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8122a78f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8122c1f4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81232c00)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8123bd0b)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffffffff81251ace)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffffffff8125d532)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffff8125e13f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125f4ff)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126c8e5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127349e)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffff8127c8fa)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8127fed9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81284945)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812878b7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81290390)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff81293562)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8129a55b)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (ffffffff812a45fb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8b6b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (ffffffff812b2424)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (ffffffff812b6e0d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812be48b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c4bfb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812c8ece)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812caa94)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812cbef3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc3c2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ccaa2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d3db9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd874)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffffffff812df918)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e23a5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81304853)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81310949)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8131997e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffff8131e053)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8132217b)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffff81323ea7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81336088)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8133966a)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffff81347cf7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff81349900)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81353f43)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135776a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135d619)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffff81368c29)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139ffa1)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813aceb7)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffff813b40cc)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffff813bb4ae)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c4e2e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813e0846)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e7525)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ec3da)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f6126)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f86e2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc308)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d088)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d540)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141a452)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81422c28)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (ffffffff81429001)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814853cf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d8c07)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814f36cb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f5f69)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f6b03)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f6f3a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f7ac7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f954f)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffff814fb17f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814fb882)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814fbaa5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814fbdb7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814fc044)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814fc322)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814fd2ba)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814fd532)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816268da)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8162a16c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff8168643c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8168dea9)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171f014)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff817223fb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8178b307)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/md/md.c (ffffffff8183c3cb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818490a1)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffff818b42fa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff818bf3ec)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffff818cc383)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818fdb51)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff819023eb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819074af)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8190946f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff81963439)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff8196efc3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b6c62)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff819c489d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8127ba40-ffffffff8127ba8e: put_page (STB_LOCAL)
ffffffff8129050c-ffffffff81290557: put_page (STB_LOCAL)
ffffffff812c2770-ffffffff812c27be: put_page (STB_LOCAL)
ffffffff8139dc50-ffffffff8139dc9e: put_page (STB_LOCAL)
ffffffff814f63e0-ffffffff814f642e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8288969d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff8108ed22)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff810f6ffb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff811360c1)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811ee7d7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81200921)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81207dfc)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (ffffffff8120f5fd)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffffffff81219ae9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff8121b376)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8121d8af)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff8121f2ce)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81225ca0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8122ed0b)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffffffff81244af9)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffffffff8124f982)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
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
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mincore.c (ffffffff812505cf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125191f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8125e937)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8126540e)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffff8126e7aa)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff81271c63)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812767b5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81279717)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81282020)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff81285172)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8128c11b)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (ffffffff812960cb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129a52b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (ffffffff812a37b0)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (ffffffff812a7fdd)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812af54f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b5c3b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812b9f0e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812bb9da)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812bcd63)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd232)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812bd912)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812c4a39)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce4f4)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffffffff812d0558)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812d2fe5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff812f5473)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff81301559)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8130a53e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffff8130ebf3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff81312d1b)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffff81314a47)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81326d78)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8132a39a)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffff813389d7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8133a5e0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81344c03)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8134841a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8134e2b9)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffff81359ef4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff81390a31)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8139d947)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffff813a4b5c)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffff813abf3e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813b58ae)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813d12c6)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813d7fa5)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813dce5a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813e6ba6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813e9162)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecd88)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdb08)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff813fdfc0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140aed2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff814136a8)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (ffffffff81419a81)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81475def)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814c95b7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814e3bdb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814e6479)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814e7013)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814e744a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814e7fd7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814e9a5f)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffff814eb68f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814ebd92)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814ebfb5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814ec2c7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814ec554)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814ec832)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814ed7ca)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814eda42)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161af5a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81664395)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff8166b899)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8444)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff816fb82b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff8176ac57)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d381)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff81803a2b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff81810701)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffff8186e24a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8187932c)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffff81886413)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff818b7981)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff818bc21b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff818c12bf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff818c327f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff8191cf29)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff81928ab3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81973a52)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff8198168d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff812478e0-ffffffff8124792e: put_page (STB_LOCAL)
ffffffff8126d920-ffffffff8126d96e: put_page (STB_LOCAL)
ffffffff8128219c-ffffffff812821e7: put_page (STB_LOCAL)
ffffffff812b37c0-ffffffff812b380e: put_page (STB_LOCAL)
ffffffff8138e6e0-ffffffff8138e72e: put_page (STB_LOCAL)
ffffffff814e68f0-ffffffff814e693e: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8289e720)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a02a6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110400b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff81140c11)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff811f985c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8120b8f1)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81212e2c)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (ffffffff8121a1b3)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffffffff81224719)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff81225fd6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8122852f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81229f94)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812309a0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff81239aab)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffffffff8124f86e)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffffffff8125b2d2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffff8125bedf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8125d29f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8126a685)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff8127123e)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffff8127a69a)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8127dd32)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81282755)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff812856c7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128e1a0)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff81291372)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff8129836b)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (ffffffff812a240b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a697b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (ffffffff812b0234)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (ffffffff812b4c1d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812bc29b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2a0b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812c6cde)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812c88a4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812c9d03)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca1d2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812ca8b2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812d1bc9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db684)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffffffff812dd728)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812e01b5)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81302643)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8130e739)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8131744e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffff8131bb23)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8131fc4b)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffff81321977)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81333b58)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8133713a)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffff813457c7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff813473d0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81351a13)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff8135523a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8135b0e9)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffff813666f9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139d801)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813aa717)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffff813b192c)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffff813b8d0e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813c22be)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813ddbc6)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813e48a5)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813e975a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff813f34a6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff813f5a62)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9688)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a408)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a8c0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814165f2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff8141edc8)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (ffffffff814251a1)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148146f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814d4c97)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff814ef75b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff814f1ff9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff814f2b93)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff814f2fca)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff814f3b57)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff814f55df)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffff814f720f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff814f7912)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff814f7b35)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff814f7e47)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff814f80d4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff814f83b2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff814f934a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff814f95c2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816548aa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8165813c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816b4ae5)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816bc119)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175dde4)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff817611cb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817bb6a7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8151)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff8188b9fb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818986d1)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffff819052fa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff819103ec)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffff8191d383)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff8194eb81)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff8195341b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff819584df)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8195a49f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819cdc09)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819d9793)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a216e2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f31d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff812797e0-ffffffff8127982e: put_page (STB_LOCAL)
ffffffff8128e31c-ffffffff8128e367: put_page (STB_LOCAL)
ffffffff812c0580-ffffffff812c05ce: put_page (STB_LOCAL)
ffffffff8139b4b0-ffffffff8139b4fe: put_page (STB_LOCAL)
ffffffff814f2470-ffffffff814f24be: put_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8289e725)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/exit.c (ffffffff810a822a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/power/swap.c (ffffffff8110f3fb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/futex.c (ffffffff8114de6c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/bpf/stackmap.c (ffffffff81208310)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8121a701)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81221da3)
Location: include/linux/mm.h:1036
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
In mm/filemap.c (ffffffff8122928a)
Location: include/linux/mm.h:1036
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
In mm/page-writeback.c (ffffffff812339e9)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffff812352d6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffff8123789f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffff81239381)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123fdf0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8124919b)
Location: include/linux/mm.h:1036
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
In mm/gup.c (ffffffff8125f1de)
Location: include/linux/mm.h:1036
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
In mm/memory.c (ffffffff8126ac9c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
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
In mm/mincore.c (ffffffff8126b8cf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffff8126cc8f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff8127a063)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/process_vm_access.c (ffffffff81280cae)
Location: include/linux/mm.h:1036
Inline: True
```
```
In mm/madvise.c (ffffffff8128a27a)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swap_state.c (ffffffff8128d8e2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8129243c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffffffff81294ceb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129df3e)
Location: include/linux/mm.h:1036
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
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff812a1180)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/ksm.c (ffffffff812a8163)
Location: include/linux/mm.h:1036
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
In mm/memory_hotplug.c (ffffffff812b276b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b6cab)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
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
In mm/huge_memory.c (ffffffff812c0574)
Location: include/linux/mm.h:1036
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
In mm/khugepaged.c (ffffffff812c4a58)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812cca6c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d34ab)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/zsmalloc.c (ffffffff812d7330)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffff812d9561)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffff812da9fe)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812daed2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (ffffffff812db5e2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
```
In fs/read_write.c (ffffffff812e2a07)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec618)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/pipe.c (ffffffff812ee6a8)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffff812f1a95)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81313c63)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/splice.c (ffffffff8131ff39)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/buffer.c (ffffffff8132903e)
Location: include/linux/mm.h:1036
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
In fs/block_dev.c (ffffffff8132d903)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
```
```
In fs/direct-io.c (ffffffff8133196b)
Location: include/linux/mm.h:1036
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
In fs/mpage.c (ffffffff813336d7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/aio.c (ffffffff81345bc6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffff8134a1fa)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/verity/enable.c (ffffffff81358aa7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffff8135a6d0)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffff81364fae)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81368815)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/iomap/buffered-io.c (ffffffff8136e865)
Location: include/linux/mm.h:1036
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
In fs/proc/task_mmu.c (ffffffff81379a37)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813b1d71)
Location: include/linux/mm.h:1036
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
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813bf008)
Location: include/linux/mm.h:1036
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
In fs/ext4/mballoc.c (ffffffff813c6460)
Location: include/linux/mm.h:1036
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
In fs/ext4/move_extent.c (ffffffff813cda2e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/readpage.c (ffffffff813d743a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffff813f2fe6)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/ext4/verity.c (ffffffff813f9ce2)
Location: include/linux/mm.h:1036
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff813ff05e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffff814090b6)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8140b6b2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f2e3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffff8142010c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffff81420580)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142d352)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffffffff81435b28)
Location: include/linux/mm.h:1036
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
In fs/fuse/readdir.c (ffffffff8143c078)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81498ff3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In block/bio.c (ffffffff814ed847)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/partition-generic.c (ffffffff815087eb)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffff8150b059)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffff8150bbf3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
Direct callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffff8150c02a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffff8150cbb7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffff8150e63f)
Location: include/linux/mm.h:1036
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
In block/partitions/msdos.c (ffffffff8151026f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
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
In block/partitions/osf.c (ffffffff81510972)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffff81510b95)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffff81510ea7)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffff81511134)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffff81511412)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffff815123aa)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffff81512622)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f32a)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffffffff8167273c)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/char/virtio_console.c (ffffffff816ced8c)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/char/agp/generic.c (ffffffff816d6a09)
Location: include/linux/mm.h:1036
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779444)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffff8177c82b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/net/tun.c (ffffffff817d46e2)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e23f1)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/md/md.c (ffffffff818aac6b)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
```
```
In drivers/md/md-bitmap.c (ffffffff818b5731)
Location: include/linux/mm.h:1036
Inline: True
```
```
In net/core/sock.c (ffffffff819263ea)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffffffff8193154c)
Location: include/linux/mm.h:1036
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
In net/core/dev.c (ffffffff8193e8a3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/filter.c (ffffffff81970551)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffff81974f2e)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff8197a60f)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197c6bf)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/ipv4/tcp.c (ffffffff819d7799)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffffffff819e33f3)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2ca32)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ac6d)
Location: include/linux/mm.h:1036
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff812893d0-ffffffff8128941e: put_page (STB_LOCAL)
ffffffff8129e0ad-ffffffff8129e0f8: put_page (STB_LOCAL)
ffffffff812d1020-ffffffff812d106e: put_page (STB_LOCAL)
ffffffff813af970-ffffffff813af9be: put_page (STB_LOCAL)
ffffffff8150b4d0-ffffffff8150b51e: put_page (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
