# Function: <code>pagefault_disable</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101cc2f)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e71a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81075f8c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In kernel/futex.c (ffffffff810fffc5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:futex_wake_op
```
```
In kernel/kexec_core.c (ffffffff8110c837)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811379ec)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace.c (ffffffff8114f5c8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811674a8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff81186ffd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_from_page
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff8119152b)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/page_alloc.c (ffffffff81196092)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff8119f233)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811a8626)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_symlink
```
```
In mm/memory.c (ffffffff811bc4ca)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/vmalloc.c (ffffffff811cf6f0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vwrite
```
```
In mm/swapfile.c (ffffffff811d375e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/zswap.c (ffffffff811d8807)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff811e49de)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff811f1e1e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f5478)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/zsmalloc.c (ffffffff812054ff)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
```
```
In mm/userfaultfd.c (ffffffff81207880)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81213206)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In fs/namei.c (ffffffff81216a6e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/libfs.c (ffffffff81234b63)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81244473)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_writepage
```
```
In fs/direct-io.c (ffffffff8124a4dc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124dc51)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8125bb14)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:do_io_submit
```
```
In fs/dax.c (ffffffff8125dec2)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
```
```
In fs/ext4/inode.c (ffffffff81297720)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff812a0041)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d682e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e04cb)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff812e2ee0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff812e875c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff812ea1bd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2ba0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/mmap.c (ffffffff81303eb1)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81304a0c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8130e2c1)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81315abc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
```
```
In security/tomoyo/domain.c (ffffffff8136df18)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8139e783)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ahash.c (ffffffff813a29e5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff813a3cbe)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/shash.c:shash_compat_digest
```
```
In block/bio.c (ffffffff813b122c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff813d508d)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e7605)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In arch/x86/lib/usercopy.c (ffffffff813f78da)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/scatterlist.c (ffffffff813fa4a0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/iov_iter.c (ffffffff813fb8bb)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff814c64f6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815175e8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/brd.c (ffffffff8156d394)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (ffffffff8157049e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81573d66)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae369)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf822)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8169c659)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_print_sb
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
```
In net/core/skbuff.c (ffffffff81706639)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff810079aa)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e5d2)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810774d8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In kernel/futex.c (ffffffff811080e4)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff811140a7)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113feb4)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace.c (ffffffff8115859a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174a5d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff8119b40c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811a5e79)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811aa0af)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811b4e8b)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c0075)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811ddd92)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff811ecc22)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff811f15ad)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff811f68ff)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81205d9e)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
```
```
In mm/migrate.c (ffffffff81210886)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81216c3c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121b017)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff8122bfca)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8122d151)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81239cf7)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In fs/libfs.c (ffffffff8125d061)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8126cea3)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81272e9d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812763b5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812861dc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81287bba)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In fs/iomap.c (ffffffff8129c6a5)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c64a1)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce9d2)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813064cc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310f5f)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81312db6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81316371)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317cdc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813207eb)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8132272a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81324935)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81324eb0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81325444)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813388e6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81338b2c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81342a8c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134a3fe)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/tomoyo/domain.c (ffffffff813a41c8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813db6a9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813dd60b)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813deb78)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff813dff7a)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In block/bio.c (ffffffff813f4bfc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8141ad4d)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d878)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e763)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/scatterlist.c (ffffffff81441517)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/iov_iter.c (ffffffff814441ee)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81516c1d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8156a29d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/brd.c (ffffffff815c3290)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (ffffffff815c5dae)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815cae60)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8160623f)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff81618235)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff81700b20)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In net/core/skbuff.c (ffffffff817700d6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff810079f6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103df32)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b088)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In kernel/futex.c (ffffffff8110f8d4)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8111b7bb)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149c9a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff811804dd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811aae00)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811b61f9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811ba5e9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811c54ad)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d023b)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811edba8)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff811fdeba)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81201fbd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812072af)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81217dae)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff812229ea)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81229168)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122d3d9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff8123e50a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8123f67a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8124468b)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8124ca38)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In fs/libfs.c (ffffffff812705a7)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81280133)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812869b0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128a0f5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812995f9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8129c384)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812b13c5)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dbd4d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e47cd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c48c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326e36)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81328d66)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8132c361)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132dcce)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81336689)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813385ba)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8133a79a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8133ad0a)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8133b294)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e686)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e8cc)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813588a9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8135fc13)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/tomoyo/domain.c (ffffffff813bad49)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813f2fe6)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813f4edb)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In crypto/ahash.c (ffffffff813f7118)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff813f850a)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In block/bio.c (ffffffff8140e5e9)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8143628c)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In block/bio-integrity.c (ffffffff81447632)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff81448d99)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b743)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/scatterlist.c (ffffffff8145e731)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In lib/iov_iter.c (ffffffff814623e5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81543089)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815969dd)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff815f430d)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815f7aa0)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8163575c)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff81647dd5)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:25
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff81732890)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In net/core/skbuff.c (ffffffff8179d246)
Location: include/linux/uaccess.h:25
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff81007768)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf35)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81079866)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In kernel/futex.c (ffffffff81110ca9)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8111d51c)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114ba9d)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182fd4)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811b2267)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811be109)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811c25bb)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811cd956)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d8cdf)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811f8d38)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81208a9d)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8120c84f)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8121242f)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812239b2)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff8122e457)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81235567)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81238f94)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff81249f02)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8124afe7)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812500ce)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff81258aeb)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In fs/libfs.c (ffffffff8127dcb6)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8128da33)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff8129404e)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81296c5f)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812a72aa)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812ab4a5)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812be879)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fad2e)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81300591)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81315037)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e49c)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131e821)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81341607)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342e59)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8134b38b)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8134d53f)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8134f41c)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8134f945)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8134fdc6)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813631e7)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813633e9)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8136d105)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813747f8)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/tomoyo/domain.c (ffffffff813d15ee)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813ff35b)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8140120b)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In crypto/ahash.c (ffffffff814034e8)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81404a27)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8141c12c)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff81442db3)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81455a30)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff81457309)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8146393e)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In lib/iov_iter.c (ffffffff814680de)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:185
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81556f39)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815aa7d3)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81605c4d)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b956)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164a916)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c90c)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff8167dd68)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/bitmap.c (ffffffff8174b6bc)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff8174c1cc)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff8175c5ce)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff817b793d)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4ba)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff818fd89a)
Location: include/linux/uaccess.h:185
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff81007bae)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb23)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107fbd5)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In kernel/futex.c (ffffffff8111d584)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81128c6c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158369)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c44)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811c5e77)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811d2dce)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811d7038)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811e2c46)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811edf2d)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812110ca)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81221d17)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81226578)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8122d07f)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8123eff2)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff8124a6b8)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81253f28)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a20)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff8126a12e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8126b943)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81272034)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127ac66)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/libfs.c (ffffffff812a0793)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812b05ed)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812b7461)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9eca)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812ca6cd)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812cedeb)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812e22fd)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131f41e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81324db4)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81339dd2)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342abc)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813431ac)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81365c39)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367526)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8136f9b8)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81371bef)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81373b33)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813740aa)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81374546)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81387eab)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8138817f)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81391d4a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813997fd)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/tomoyo/domain.c (ffffffff813f7aae)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8142796e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8142981b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In crypto/ahash.c (ffffffff8142bc18)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8142d33b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81446dca)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8146f897)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8148170c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff81483016)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8148f8de)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In lib/iov_iter.c (ffffffff814943cb)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815baf5a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81611159)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8166e04d)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816743e7)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b3c86)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5fba)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff816e760a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff817bda5a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
  - drivers/md/md-bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff817be5c5)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff817ce820)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff81830066)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff81984f91)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8198538a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff810081e0)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810400f1)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81082cf0)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (ffffffff810ec2a5)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In kernel/futex.c (ffffffff8112b32a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81136cfd)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f85)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6164)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811e63f5)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811f4152)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811f84d0)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff812041fc)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8120f3c8)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81231aca)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81243c1b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff81249888)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8124fd06)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8126279e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81262b20)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8126d9f3)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8127391b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127b809)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e8d1)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff8129036c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff8129806f)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/exec.c (ffffffff812a1a16)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/libfs.c (ffffffff812c6d05)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812d83db)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812e002d)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e2c7c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812f4861)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff812f953d)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/iomap.c (ffffffff8130ec59)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134d502)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81353012)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81368326)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370a0c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81370f0f)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813943ab)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395dc3)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8139ded4)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813a01ac)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813a256a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813a2d82)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813a2f56)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a2d)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813b6fd4)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c0d83)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813c83e9)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In security/tomoyo/domain.c (ffffffff81428a7e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8145a7ce)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8145c887)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In crypto/ahash.c (ffffffff8145e929)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8145ffa7)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81479f04)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814a3c67)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814b61cf)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff814b7c6e)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff814c45be)
Location: include/linux/uaccess.h:186
Inline: True
```
```
In lib/iov_iter.c (ffffffff814c980b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/balloon.c (ffffffff815f360a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8164abd9)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816a9b2d)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816b0592)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816efd2b)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff81702544)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff81723d4a)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81805a5c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:bitmap_file_set_bit
  - drivers/md/md-bitmap.c:bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff818068b9)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff8181748c)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8187a0f3)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff819e148f)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e18da)
Location: include/linux/uaccess.h:186
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff810080c0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416b1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810898a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (ffffffff810f7945)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff81134f79)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8114235d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173ce5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811e084b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff811f6f45)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff812064e2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff8120a8c7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff81216bbc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81221bfa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8124529a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8125831b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8125deb5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81264276)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8127701e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812773a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff81281ff9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81287ebe)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8128fbc4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff812a2a71)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812a5305)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812ad2f0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b67d6)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff812dbed5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812ed8ab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff812f4b59)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f78de)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8130970e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8130d70a)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/iomap.c (ffffffff813243dd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff81365692)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8136b13f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813807a9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388ea1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813893b1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813ad0fb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeb19)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813b6c44)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813b8f2d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813bb34a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813bbb8f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813bbd56)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff7d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813d0524)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813da0e3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813e1610)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In fs/fuse/readdir.c (ffffffff813e9ddb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8144534e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8147833e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81479ef7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff8147c299)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8147da37)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81497d18)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814be4f5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814c9acf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff814cb080)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/scatterlist.c (ffffffff814d8cb1)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff814de809)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff8160cd15)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e689)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81668e99)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816ca76d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816d075f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171358b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8172319f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8174666a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81831c5f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81842d2c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8189acfd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c43f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c89a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff810082cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f2cb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043bbe)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108cdb8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff810ffef6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff8113e3b5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8114d773)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180ae0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811f6451)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8120f0c1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff8121da82)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff81226572)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123146c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812572e3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81268c99)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8126d4d3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8127904e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8127f1cd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8129287c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81292ce5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8129e122)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a2ae1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812aac65)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff812bdf6f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812c0ab8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c9c76)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d36c2)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff812fa57c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130f069)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81315f11)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81317f29)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8132b8ab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81335924)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8134c51c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8138e9d5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139467f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a95da)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2fa5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b3584)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813d73b3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d9004)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e1328)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e3d43)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e5bfe)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e6424)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e65f6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab6c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb142)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81406220)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff8140d2e0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_short_read
```
```
In fs/fuse/readdir.c (ffffffff81415f4f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81472fcb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a6181)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814a7dad)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814aa589)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814abcd2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c59c1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814ecc8b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814f81aa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff814f99d5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/scatterlist.c (ffffffff81504b64)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff8150a3a4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff816419c0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81642416)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8169e809)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81705d2c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8170a458)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174ee71)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817605ee)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff81782343)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818743ff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81885b24)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff818e564f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c0ef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c4d0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff810085cf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f94d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104430e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108da18)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff8110c356)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff81149f45)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff81159483)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c950)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff8120340f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8121c3a9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff8122b522)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff812343de)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123f52c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff81245c1a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81265873)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812775d1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8127c013)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff81288b2e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128ec2d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812a25ff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a2a65)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812ad9d2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b3fd4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bc236)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812cfe5f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812d2868)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812db754)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e5252)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff8130c2fc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81323bf3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81328d91)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132ad9f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8133e6fb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81349524)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff813510cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813647ec)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813a7435)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813acfff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c24fa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cc027)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc77a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813eedd7)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813f13e3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f2ffd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813fb378)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813fdd85)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813ffc4e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140049a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81400676)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81414a3c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81415012)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81420d80)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff814286e7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8142fe2f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148cd6b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814c0e11)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814c2a0d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814c5249)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814c69b2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814debc1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff815060d8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81515f8a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81517760)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81522ca4)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff815284de)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81662fd0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816649df)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816c18b9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81729f7c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8172e758)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177304d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8178457f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff817a5ff3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818a620f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818b7ac4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff819177a4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac33af)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3790)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff8100954b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042cbc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047d47)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81117185)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff8115a976)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8116a558)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a130e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff8122b188)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/events/core.c (ffffffff81231e1c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81246ec9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8124ca76)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In mm/maccess.c (ffffffff81258420)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff812619ab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126cd6f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8127399a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81295bcb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812a743b)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In mm/page_alloc.c (ffffffff812ae33d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812bb7ce)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812c19b5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812d6d26)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812d7271)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:poison_pages
```
```
In mm/migrate.c (ffffffff812e2ea8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812f176e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In mm/zsmalloc.c (ffffffff81306fbf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff813082b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffffffff81311700)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/exec.c (ffffffff8131c474)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff813457e2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8135ca63)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff81362e3c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8136480b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813783a7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8138e89f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff81397b3c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813aca7f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813f35d5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813f932d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8140ec0f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81418150)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418ae3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8143c3b7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8143c91d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff814408d9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff81448aef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8144b7e3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8144d60c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8144deac)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8144e028)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81462cc2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814632d2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8146fe09)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff814763be)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8147fda9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff814e3ff7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff815216bb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff815241c8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81525c7b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8153e57c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff81566c7f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81576923)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81577f21)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81585cbe)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff8158837d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff8e8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ffc90)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff81713504)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8171455f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81774e38)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817e8005)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817eec6f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834cde)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8184436f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8186a2cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81976292)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81987d3e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In net/core/skbuff.c (ffffffff819ec58f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff81008636)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042c52)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047203)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066186)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066de9)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067f5a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff8108728e)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81112221)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In kernel/futex.c (ffffffff811575dc)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81166c98)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e45e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff812330bc)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In kernel/events/core.c (ffffffff8123ba8c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81251527)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81256eb6)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In mm/maccess.c (ffffffff81262bb5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff8126ad88)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In mm/shmem.c (ffffffff81277814)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8127e22a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff812a0b76)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff812b26bb)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b9f56)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812c726e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812cd629)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff812e28b6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812e2d7a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812ee2e8)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812fdcc3)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff81312cff)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_alloced_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff8131404a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff81327954)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81351fd9)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff81366a80)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/buffer.c (ffffffff813675e4)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3a8)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/mpage.c (ffffffff813712a3)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/aio.c (ffffffff813860ae)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8139fffd)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff813a93bc)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813bca37)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end_inline
```
```
In fs/ext4/inline.c (ffffffff81405d65)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814083f4)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d18)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142aec3)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c67a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff81458707)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff81458c9d)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff8145cb06)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff814656e6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81467ec3)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81469c4c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146a463)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146a5c8)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e544)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eb22)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148a6a6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81490e29)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8149b489)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff81501418)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8153e52b)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In crypto/ahash.c (ffffffff81541015)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81542bab)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8155af76)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff81581ae5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff815932f1)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81594ba1)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a2d9e)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a802b)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copy_mc_pipe_to_iter
  - lib/iov_iter.c:csum_and_copy_to_pipe_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In arch/x86/lib/usercopy.c (ffffffff81624818)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624b80)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff817303f4)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730c3f)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8178fb88)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817fcf65)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8180356f)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81845dae)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81854688)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff818790dc)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8197b282)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc6e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bed7b)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff819ec338)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff81008ff4)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104462d)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048daf)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810665e6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067397)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810684cd)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff81087ec2)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81113fcd)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In kernel/futex.c (ffffffff81158a2c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81167a32)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f17c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff8124013c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81257824)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8125b346)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In mm/maccess.c (ffffffff812675d5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff8126ff3a)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In mm/shmem.c (ffffffff8127c674)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8128339a)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff812a64b6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff812bd889)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff812bf3f9)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812cdb8e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812d40a8)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff812ea046)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812ea4a2)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812f4411)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81304e39)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff8131800b)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff8131a1f5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8132d707)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81358ce9)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff8136d330)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/buffer.c (ffffffff8136e026)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/direct-io.c (ffffffff81375c5a)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/mpage.c (ffffffff81377c55)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/aio.c (ffffffff8138d1fe)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813a7593)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff813b08f3)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813c4a9e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/ext4/inline.c (ffffffff8140c0a5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140e706)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142851a)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a35)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433349)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff814603c3)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8146219d)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8146ae89)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8146d4c6)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8146f348)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146fb36)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146fc88)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81484018)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814846af)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81490175)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8149bc22)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814a0699)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814a1aae)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/tomoyo/domain.c (ffffffff81507ef8)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81546bfb)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In crypto/ahash.c (ffffffff81549679)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8154b24c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff815637a7)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff8159a0f3)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8159b967)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a9cce)
Location: include/linux/uaccess.h:244
Inline: True
```
```
In lib/iov_iter.c (ffffffff815b34b1)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
```
In lib/buildid.c (ffffffff815efec5)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81608208)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81608530)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff81713f94)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817147cb)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff817726f8)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817e19f2)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7d35)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182904e)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81838228)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8185b91c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/md/md-bitmap.c (ffffffff8195f49f)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81970a92)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff819a347c)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff819d282f)
Location: include/linux/uaccess.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff81009ec3)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a5ea)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f79f)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070730)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107170b)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072982)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff81097242)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811340d1)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In kernel/futex.c (ffffffff8117d91c)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8118d2c6)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8ffc)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff8127ab1c)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812910c1)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8129714c)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In mm/maccess.c (ffffffff812a4015)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff812ad33a)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In mm/shmem.c (ffffffff812ba884)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812c155a)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:copy_huge_page
  - mm/util.c:copy_huge_page
```
```
In mm/memory.c (ffffffff812e7976)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff81300078)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81301575)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In mm/swapfile.c (ffffffff8131300e)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81319d72)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff81331f68)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813323c2)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8133e778)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8134ebcc)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff81364511)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff81366382)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_freepage
```
```
In mm/userfaultfd.c (ffffffff8136712d)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8137af37)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff813a7349)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff813bc010)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/buffer.c (ffffffff813bcd90)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/direct-io.c (ffffffff813c208d)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/mpage.c (ffffffff813c42e5)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/aio.c (ffffffff813da95e)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813f4d70)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/verify.c (ffffffff814004d3)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff814121b0)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145efa5)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814615e0)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c21d)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485255)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814864e5)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff814b5846)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b7693)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814c1699)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff814c3d5e)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff814c5d38)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c658c)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff814c66f8)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814db2f6)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbd2f)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e7ba3)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff814f3619)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814f8566)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814f9b81)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/tomoyo/domain.c (ffffffff81565136)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff815a73db)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In crypto/ahash.c (ffffffff815a9e59)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff815aba2c)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff815c6c5c)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In lib/scatterlist.c (ffffffff81612e10)
Location: include/linux/uaccess.h:234
Inline: True
```
```
In lib/iov_iter.c (ffffffff81614daa)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/buildid.c (ffffffff8165d165)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e48)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81677170)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff817909cf)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8179160b)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff817f7f28)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8186d6e2)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81873c58)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b4a1c)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff818c5162)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff818eb382)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/md/md-bitmap.c (ffffffff81a04dee)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81a193b2)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81a506fc)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81a823ff)
Location: include/linux/uaccess.h:234
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff81009612)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810549fb)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105aad0)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dd07)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f76f)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080ce0)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff810a9d72)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In kernel/futex/core.c (ffffffff811b3145)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811b6734)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcaf0)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff812cdb06)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e65c2)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff812ecfc1)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In mm/maccess.c (ffffffff812fc0d5)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff8131cbaf)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff8131e561)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81348b35)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8136297a)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In mm/swapfile.c (ffffffff8137e2c4)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8138566a)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff8139e441)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813a37e8)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff813e249d)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff813e4716)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff813fb214)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/aio.c (ffffffff81465366)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8146794e)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/verify.c (ffffffff8147440a)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/ext4/inline.c (ffffffff814dd7b8)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff8153d464)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540e5f)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8154c022)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8154ead0)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550c9f)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815516b5)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81551858)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81568b7d)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff815699b0)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff81600939)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8164e734)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In crypto/ahash.c (ffffffff8165136d)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81653343)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff816df42a)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e2d21)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/buildid.c (ffffffff817765bc)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81791ded)
Location: include/linux/uaccess.h:194
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff817921a7)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/char/virtio_console.c (ffffffff8193651f)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb697)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff9c6)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bcf2)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81b6cae5)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81b81ffa)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf5c3)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81bf77bc)
Location: include/linux/uaccess.h:194
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
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
In arch/x86/events/core.c (ffffffff8100aab2)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062558)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810688a0)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810c3342)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f4045)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811f7884)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244218)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff813390c5)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81350098)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81357341)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In mm/maccess.c (ffffffff81366325)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff81390660)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff81392041)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff813c0fa2)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff813de33a)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In mm/swapfile.c (ffffffff813fbed4)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814033d3)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff8141db61)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81423578)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff81468253)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_tagged_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff8146c727)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/aio.c (ffffffff814f53a6)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814f800e)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/ext4/inline.c (ffffffff815767e8)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff815dbc93)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff815dffb2)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff815ebdf2)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff815ef551)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1977)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c4ad)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d5e1)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff816b1889)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81707b94)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In crypto/ahash.c (ffffffff8170abfd)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8170d063)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff817cf65a)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d54c0)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81a9635f)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30be7)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e01b)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1142)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81d08bf5)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d2081d)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63de3)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81da586c)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff8201f009)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fc1d)
Location: include/linux/uaccess.h:203
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ff77)
Location: include/linux/uaccess.h:203
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff8100a308)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064028)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106a191)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810c6a62)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In kernel/futex/core.c (ffffffff812087d5)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8120c2d4)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b2f8)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_events_user.c (ffffffff812c3b31)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/events/core.c (ffffffff8136a6c9)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81381271)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81388bbc)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In mm/maccess.c (ffffffff813987c5)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff813c2fab)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff813c4a41)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff813f5d47)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/swapfile.c (ffffffff8142efe4)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8143689a)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff814525c1)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81458818)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff8149e12e)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff814a1435)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff8152f20e)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/jbd2/transaction.c (ffffffff81613753)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff816172ce)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff816238d2)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81627531)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629a67)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/ecryptfs/mmap.c (ffffffff8164439d)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8164549c)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff816ea28c)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In lib/scatterlist.c (ffffffff8180db0a)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813ef0)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81ae1b6f)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81b842a7)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1dfb)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c18c22)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81d71d68)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d899fd)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcef33)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81e13d7b)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff8209f01c)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce146)
Location: include/linux/uaccess.h:225
Inline: True
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
In arch/x86/events/core.c (ffffffff8100fa28)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b540)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81071661)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810ceee2)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121f665)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff812235d4)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812751fc)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_events_user.c (ffffffff812e0381)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/events/core.c (ffffffff81393059)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813aa621)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff813b261c)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In mm/maccess.c (ffffffff813c25c5)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff813edaea)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81421a24)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/zsmalloc.c (ffffffff814cd278)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff814d0bc8)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff815640ee)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/squashfs/file.c (ffffffff81660691)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662cb7)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In security/tomoyo/domain.c (ffffffff81726f9c)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In lib/scatterlist.c (ffffffff818537ba)
Location: include/linux/uaccess.h:225
Inline: True
```
```
In lib/iov_iter.c (ffffffff81858305)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81b34f5f)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd81d7)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c26a6b)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d972)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c81278)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
```
```
In drivers/md/md-bitmap.c (ffffffff81e28e38)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81e41195)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87c63)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81ed0f3b)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff8217701c)
Location: include/linux/uaccess.h:225
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8976)
Location: include/linux/uaccess.h:225
Inline: True
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
In arch/arm64/kernel/perf_callchain.c (ffff8000100a3564)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm64/kernel/probes/uprobes.c (ffff8000100ac73c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol
```
```
In virt/kvm/kvm_main.c (ffff8000100bde0c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_map_gfn
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffff8000101bb5b8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffff8000101c89c0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203c6c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffff80001028bb88)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff800010298548)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (ffff8000102a5928)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffff8000102b9fb4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffff8000102c4a00)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d0d40)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffff8000102d9320)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffff8000102fc1e4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffff80001030da8c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffff8000103135b8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffff800010323aec)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffff80001032b940)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffff800010341ff0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffff800010342b08)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffff80001034f9dc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffff800010355688)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035d3c8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffff800010374874)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffff800010378278)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffff80001038063c)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/exec.c (ffff80001038c32c)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffff8000103c0b08)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffff8000103dcf84)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffff8000103e42a8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e641c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffff8000103fddb0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffff80001040a194)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffff80001041312c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffff80001042b310)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffff80001047acb4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104818b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff800010499f2c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a40a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4c04)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffff8000104c8100)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104cb3a4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce678)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffff8000104d89cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffff8000104dbe38)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddc84)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de490)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffff8000104de708)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f61ec)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffff8000104f6640)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff800010503a48)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffff80001050aaf8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffff800010514848)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffff800010580244)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffff8000105bb09c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffff8000105bd1e4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffff8000105bfe2c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffff8000105c1e18)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffff8000105dadd4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (ffff80001061d384)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffff80001061ec38)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffff80001062c844)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffff800010632b80)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffff80001082cd18)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffff80001082e774)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffff8000108b2b84)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffff800010920c14)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffff800010925668)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffff80001097662c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffff80001098ad50)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffff8000109b2328)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffff800010afb140)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffff800010b0fe74)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffff800010bb0b14)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
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
In arch/arm/kernel/perf_callchain.c (c0317cd8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm/mm/highmem.c (c0321ccc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
```
```
In kernel/futex.c (c0400488)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/events/core.c (c04ceb9c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/uprobes.c (c04d6fb8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (c04e60cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
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
In arch/powerpc/kernel/traps.c (c00000000002e820)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:handle_hmi_exception
```
```
In arch/powerpc/mm/fault.c (c000000000086ba8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/mm/hugetlbpage.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In arch/powerpc/lib/vmx-helper.c (c0000000000b412c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/powerpc/lib/vmx-helper.c:enter_vmx_usercopy
```
```
In arch/powerpc/perf/callchain.c (c000000000125164)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_64
```
```
In arch/powerpc/perf/core-book3s.c (c000000000128ea4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (c00000000021ca7c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (c0000000002312d8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e4bc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (c000000000337bd4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000342830)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (c00000000035b490)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (c000000000371fa8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (c00000000037f1a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c000000000390f60)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (c000000000398f20)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (c0000000003c7a44)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (c0000000003de664)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (c0000000003e5260)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (c0000000003f88b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (c0000000004027a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (c00000000041f838)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (c00000000041ff80)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (c0000000004323e8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c00000000043cc98)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000448e5c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (c000000000467f58)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (c00000000046b0c8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c0000000004771fc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (c000000000484c80)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (c0000000004bf2b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (c0000000004e2650)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (c0000000004ea38c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec670)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c000000000507328)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (c000000000516190)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (c000000000520e98)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (c00000000053bc30)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (c00000000059dd68)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a5e98)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c424c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d12a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d1da4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (c0000000006008c8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c000000000604454)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0000000006070e4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (c000000000613924)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (c0000000006170ec)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c00000000061980c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a3b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (c00000000061a574)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (c0000000006370ac)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (c00000000063759c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c000000000648704)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (c000000000652e98)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (c00000000065ccd0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0000000006edb70)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (c000000000741788)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (c000000000744280)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (c000000000747cc0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (c00000000074a464)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (c00000000076bdd4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (c0000000007bbe0c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (c0000000007be1b8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (c0000000007cf3f8)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (c0000000007d62c4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (c00000000094ce6c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (c0000000009c4aec)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/scsi/scsi_lib.c (c000000000a30eb4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (c000000000a4b778)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (c000000000a7aecc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (c000000000be92d8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (c000000000c033b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (c000000000c86d24)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
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
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffe00013e798)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf652)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffe0001ce98a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/maccess.c (ffffffe0001dd2b2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffe0001e52aa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001ede9c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffe0001f36b6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffe00020b7d4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffe00021666c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffe00021a842)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffe000224396)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffe00022a576)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffe0002362b6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffe000236708)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffe00023e808)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/zsmalloc.c (ffffffe00024d71e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffe00024ff90)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffe000255b70)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffe00025dacc)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffe0002810aa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffe000295136)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffe00029a0d6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b730)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffe0002abf16)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffe0002b3c62)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffe0002bacd8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8990)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffe0003053a0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030a47c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031d5be)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325574)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325d08)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffe000341da8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffe0003441dc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000345f28)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffe00034e4a8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffe000350abc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffe0003526b8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffe000352df6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffe000352f78)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffe000365000)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffe0003652cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffe000370734)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffe00037705e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffe00037e422)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffe0003d0ebc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffe000400b7e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffe00040297e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffe000404e76)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffe000406978)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffe00041ea4c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (ffffffe0004501ae)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffe000451bb8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffe00045c95e)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffe000460f9a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (ffffffe000565830)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffe00059f512)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005decde)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffe0005ef150)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffe00060eeb8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec912)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf68)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffe000741cf4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
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
In arch/x86/events/core.c (ffffffff810085cf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103facd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104448e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c9d8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff81104576)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff81142565)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff81151aa3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f70)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811fba2f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff812149f9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff81223b72)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff8122ca2e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81237b7c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123e26a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8125dec3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8126fc21)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81274663)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8128110e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128720d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8129abdf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8129b045)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812a5fb2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ac5b4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b4816)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812c843f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812cae48)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d3d34)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd832)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff813048dc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8131c1d3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81321371)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132337f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81336cdb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81341b04)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff813496ac)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8135cdcc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139fa15)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a55df)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813baada)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c4607)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c4d5a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e73b7)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e99c3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb5dd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f3958)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f6365)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f822e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f8a7a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f8c56)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d01c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d5f2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81419360)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81420cc7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8142840f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148534b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b93f1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814bafed)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814bd829)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814bef92)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d71a1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814fe6b8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150e56a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8150fd40)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8151b284)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff81520abe)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81628e40)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a84f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81687309)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816efd5c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4748)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172773d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81738c6f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8176b0b3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8184c08f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8185d944)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff818b77a4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a621ff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a625e0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff81006dbf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f2cd)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033aae)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b508)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff810f5816)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff811358c5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff81144d83)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811780b0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811ee77a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81207769)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff81216d22)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff8121fb0e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122abbc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123126a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81250313)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff81261b91)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff812665d3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff81272f7e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8127906d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8128c79f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8128cc05)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff81297a62)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8129e661)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a587d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff812b947f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812bbdab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c49b4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce4b2)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff812f54fc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130cd73)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81311f11)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81313f1f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81327651)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff813324a1)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff8133a38c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8134da6c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813904a5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139606f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ab56a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b5087)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b57da)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813d7e37)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813da443)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc05d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e43d8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e6de5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e8cae)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e94fa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e96d6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fda9c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe072)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81409de0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81411747)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff81418e8f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81475d6b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a9e11)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814aba0d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814ae249)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814af9b2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c7b61)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814eebc8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814fe99a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81500060)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8150b574)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff81510dae)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (ffffffff81664ef9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816c9e6c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb702)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - drivers/nvdimm/pmem.c:write_pmem
```
```
In drivers/nvdimm/btt.c (ffffffff816ed0f4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_write_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_rw_integrity
```
```
In drivers/nvdimm/blk.c (ffffffff816ef236)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700b68)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8171a90f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8174af13)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818136af)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81824f14)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff818716f4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f26f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f650)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff8100858f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f90d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442ce)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c988)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff81102826)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff81140415)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8114f953)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182d40)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811f97ff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81212799)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff81221912)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff8122a7ce)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123591c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123c00a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8125bc63)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8126d9c1)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81272403)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8127ef1e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff8128501d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812989ef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81298e55)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812a3dc2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812aa3c4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b2626)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812c624f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812c8c58)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d1b44)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db642)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff813026cc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81319ca3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff8131ee41)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81320e4f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813347ab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8133f5d4)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff8134717c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8135a89c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139d275)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a2e3f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b833a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c1a97)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c21ea)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e4737)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e6d43)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e895d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f0cd8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f36e5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f55ae)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f5dfa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f5fd6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a39c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a972)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81415500)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff8141ce67)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814245af)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814813eb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b5481)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814b707d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814b98b9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814bb022)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d3231)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814fa748)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150a5fa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8150bdd0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81517314)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff8151cb4e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81656e10)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8165881f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816b5649)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8171d43c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81721c18)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8176650d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817793ff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8179ae73)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8189b6bf)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818acf74)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff819087a4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace5ef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace9d0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In arch/x86/events/core.c (ffffffff810086ef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040c1c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456ce)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108ecf8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff8110dc0d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In kernel/futex.c (ffffffff8114cf45)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8115c78b)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119066f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff812082a6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81221719)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff81230ad2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/truncate.c (ffffffff81239bad)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81245be2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124b731)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8126b698)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff8127d367)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81282249)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8128ddf9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812950a7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812a87a6)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a8c40)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812b465c)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ba729)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c2ccc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812d79f8)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffff812d9948)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812e295d)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec5c9)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/libfs.c (ffffffff81313cf3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8132b96a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/direct-io.c (ffffffff81330b48)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332b76)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813469b3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff81352f80)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/verity/verify.c (ffffffff8135a463)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8136dff3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813b17d4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b7512)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813cd041)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6bfe)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d7374)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813f9b5b)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fc32a)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe1ab)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814067b7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff814092fc)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b1f2)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b93e)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8140bc86)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81420093)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81420639)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142c277)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81433c4f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8143b6d5)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81498f62)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814cdf08)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfb14)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In crypto/ahash.c (ffffffff814d234f)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814d3add)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814ebc69)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff815138ee)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81523c71)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81525477)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81530aed)
Location: include/linux/uaccess.h:183
Inline: True
```
```
In lib/iov_iter.c (ffffffff815363a9)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff816713f7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e26)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816d00e0)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817387a3)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8173cfef)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781bc4)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81793226)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff817b4cfa)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818b7856)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818c91cb)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff81929833)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81adaaff)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaee7)
Location: include/linux/uaccess.h:183
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
