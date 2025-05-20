# Function: <code>pagefault_disabled_dec</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101cc4b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e70a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81075fa5)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In kernel/futex.c (ffffffff81100007)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
```
```
In kernel/kexec_core.c (ffffffff8110c86d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81137a1b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace.c (ffffffff8114f6df)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff811674e2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff81187044)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_from_page
  - kernel/events/uprobes.c:copy_from_page
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff81191540)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/page_alloc.c (ffffffff811960d0)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff8119f255)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811a865e)
Location: include/linux/uaccess.h:12
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
In mm/memory.c (ffffffff811bc51c)
Location: include/linux/uaccess.h:12
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
In mm/vmalloc.c (ffffffff811cf6fd)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vwrite
```
```
In mm/swapfile.c (ffffffff811d37fc)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff811d8869)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff811e4a30)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff811f1e1a)
Location: include/linux/uaccess.h:12
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
In mm/huge_memory.c (ffffffff811f5645)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/zsmalloc.c (ffffffff812059db)
Location: include/linux/uaccess.h:12
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff81207c8b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff812131b3)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In fs/namei.c (ffffffff81216b00)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/namei.c:__page_symlink
```
```
In fs/libfs.c (ffffffff81234b7f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_readpage
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff812444ba)
Location: include/linux/uaccess.h:12
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
In fs/direct-io.c (ffffffff8124a4a0)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124dcaf)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8125bb4d)
Location: include/linux/uaccess.h:12
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
In fs/dax.c (ffffffff8125df01)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
```
```
In fs/ext4/inode.c (ffffffff812976e7)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff812a00cb)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d683e)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0517)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff812e31c4)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff812e87ca)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff812ea2d2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff812f2bad)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/mmap.c (ffffffff81303ebe)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81304a10)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8130e310)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81315acf)
Location: include/linux/uaccess.h:12
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
In security/tomoyo/domain.c (ffffffff8136df95)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8139e925)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813a119d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/ahash.c (ffffffff813a2b6d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813a3cfe)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/shash.c:shash_compat_digest
```
```
In block/bio.c (ffffffff813b125f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff813d5156)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e76a5)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In arch/x86/lib/usercopy.c (ffffffff813f78f5)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In lib/scatterlist.c (ffffffff813fa22a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff813fb8f6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - lib/iov_iter.c:memcpy_from_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff814c655f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8151764a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/brd.c (ffffffff8156d504)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (ffffffff81570534)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81573db6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ada15)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf82b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8169b840)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_file_clear_bit
  - drivers/md/bitmap.c:bitmap_file_set_bit
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
```
In net/core/skbuff.c (ffffffff817066f3)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff8100796e)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e552)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810774dc)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In kernel/futex.c (ffffffff8110801a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff811140df)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113fee2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace.c (ffffffff811586af)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174a99)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff8119b42c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811a5eb7)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811aa0f1)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811b4ea8)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811c00ad)
Location: include/linux/uaccess.h:12
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
In mm/memory.c (ffffffff811ddda9)
Location: include/linux/uaccess.h:12
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
```
```
In mm/vmalloc.c (ffffffff811ecc1e)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff811f164b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff811f6955)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81205df2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
```
```
In mm/migrate.c (ffffffff81210897)
Location: include/linux/uaccess.h:12
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
In mm/huge_memory.c (ffffffff81216bc6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121b02a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff8122bce6)
Location: include/linux/uaccess.h:12
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff8122d5de)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81239ca3)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In fs/libfs.c (ffffffff8125d07d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8126cec3)
Location: include/linux/uaccess.h:12
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
In fs/direct-io.c (ffffffff81272f4f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8127640f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81286519)
Location: include/linux/uaccess.h:12
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
In fs/dax.c (ffffffff81287bf2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
```
```
In fs/iomap.c (ffffffff8129c6c3)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c64c6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812cea5a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813064dc)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310f9d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81312dc6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813163e0)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317dec)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff81320818)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81322782)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff813248db)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81324eb9)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8132549c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813388fe)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81338b30)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81342b4b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134a419)
Location: include/linux/uaccess.h:12
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
In security/tomoyo/domain.c (ffffffff813a423f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813db6c7)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813dd656)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813ded16)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813dffba)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In block/bio.c (ffffffff813f4c28)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8141ae0e)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d91f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e797)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In lib/scatterlist.c (ffffffff81441289)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81444278)
Location: include/linux/uaccess.h:12
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
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81516c8d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8156a2fc)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/brd.c (ffffffff815c32c7)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
  - drivers/block/brd.c:brd_do_bvec
```
```
In drivers/block/loop.c (ffffffff815c5e43)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815cb186)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605915)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff8161823e)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff81700b29)
Location: include/linux/uaccess.h:12
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
```
```
In net/core/skbuff.c (ffffffff8176deec)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff810079be)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103deb2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b08c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In kernel/futex.c (ffffffff8110f80a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8111b80d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149cce)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff81180519)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811aae20)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811b6237)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811ba62b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811c54c9)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d0279)
Location: include/linux/uaccess.h:12
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
In mm/memory.c (ffffffff811edbb5)
Location: include/linux/uaccess.h:12
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
```
```
In mm/vmalloc.c (ffffffff811fdec3)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8120200a)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81207302)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81217e04)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff812229f7)
Location: include/linux/uaccess.h:12
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
In mm/huge_memory.c (ffffffff81229164)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122cf93)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff8123e236)
Location: include/linux/uaccess.h:12
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff8123fb0d)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81244694)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8124c9df)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In fs/libfs.c (ffffffff812705c3)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81280153)
Location: include/linux/uaccess.h:12
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
In fs/direct-io.c (ffffffff81286a50)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8128a14c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81299995)
Location: include/linux/uaccess.h:12
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
In fs/dax.c (ffffffff8129c3b4)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812b13e3)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dbd72)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e4850)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c49c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326e72)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/readpage.c (ffffffff81328d76)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8132c3cd)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132ddd4)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813366c5)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8133860f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8133a73f)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8133ad13)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8133b2ec)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e69e)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8134e8d0)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8135897b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8135fc23)
Location: include/linux/uaccess.h:12
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
In security/tomoyo/domain.c (ffffffff813badba)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813f3006)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813f4f20)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In crypto/ahash.c (ffffffff813f72a6)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813f8544)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In block/bio.c (ffffffff8140e623)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8143635a)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In block/bio-integrity.c (ffffffff814476f4)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff81448da2)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b777)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In lib/scatterlist.c (ffffffff8145e429)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8146246c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81543101)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81596a3b)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff815f43a5)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff815f7dc1)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81634e35)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff81647dde)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/uaccess.h:12
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff81732899)
Location: include/linux/uaccess.h:12
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
In net/core/skbuff.c (ffffffff8179b32c)
Location: include/linux/uaccess.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff8100772a)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf2f)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107986a)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:173
Inline: True
```
```
In kernel/futex.c (ffffffff81110c05)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8111d56e)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114baf0)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff81183011)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811b2286)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811be14e)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811c25ee)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811cd999)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811d8d13)
Location: include/linux/uaccess.h:173
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
```
```
In mm/memory.c (ffffffff811f8d71)
Location: include/linux/uaccess.h:173
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
In mm/vmalloc.c (ffffffff81208aa6)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8120c8a3)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81212481)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81223a08)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff8122e4b4)
Location: include/linux/uaccess.h:173
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
In mm/huge_memory.c (ffffffff812355cb)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81238ff2)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff81249be6)
Location: include/linux/uaccess.h:173
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff8124b646)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81250177)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff81258a9d)
Location: include/linux/uaccess.h:173
Inline: True
```
```
In fs/libfs.c (ffffffff8127dcf7)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8128da78)
Location: include/linux/uaccess.h:173
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
In fs/direct-io.c (ffffffff812940d9)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81296cb6)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812a7362)
Location: include/linux/uaccess.h:173
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
In fs/dax.c (ffffffff812ab4d3)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812be88f)
Location: include/linux/uaccess.h:173
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fad6a)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813005d8)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81315047)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e4f5)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff8131e831)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8134167d)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342f43)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8134b3c8)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8134d597)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff8134f425)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8134f956)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8134fe10)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81363240)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813633ed)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8136d1d5)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81374808)
Location: include/linux/uaccess.h:173
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
In security/tomoyo/domain.c (ffffffff813d165b)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff813ff371)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81401251)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:173
Inline: True
```
```
In crypto/ahash.c (ffffffff8140360c)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff81404a60)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8141c253)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff81442e64)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81455af3)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff8145731b)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8146343b)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8146817e)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:173
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff81556f7a)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff815aa830)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81605ced)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8160bb71)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81649109)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c918)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff8167de43)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/bitmap.c (ffffffff8174b6cb)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_create
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
In drivers/md/dm.c (ffffffff8174c1d9)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff8175c61d)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff817b7410)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4e4)
Location: include/linux/uaccess.h:173
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff818fd8cb)
Location: include/linux/uaccess.h:173
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
In arch/x86/events/core.c (ffffffff81007b70)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb52)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107fbfd)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In kernel/futex.c (ffffffff8111d62f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81128cbe)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811583b0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c79)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811c5e99)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811d2e16)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811d7066)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff811e2c87)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff811edf5c)
Location: include/linux/uaccess.h:174
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
In mm/memory.c (ffffffff81211101)
Location: include/linux/uaccess.h:174
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
In mm/vmalloc.c (ffffffff81221cd1)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff812265d0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff8122d0d3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8123f048)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/migrate.c (ffffffff8124a708)
Location: include/linux/uaccess.h:174
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
In mm/huge_memory.c (ffffffff81253f77)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a70)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff8126a1dc)
Location: include/linux/uaccess.h:174
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff8126b982)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff81272095)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range_compare
  - fs/read_write.c:vfs_dedupe_file_range_compare
```
```
In fs/exec.c (ffffffff8127aca3)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/libfs.c (ffffffff812a07d4)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812b062e)
Location: include/linux/uaccess.h:174
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
In fs/direct-io.c (ffffffff812b74b3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9f21)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812ca6f7)
Location: include/linux/uaccess.h:174
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
In fs/dax.c (ffffffff812cee19)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/iomap.c (ffffffff812e2343)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8131f45a)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81324dfb)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81339e52)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342b15)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81343208)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81365cb1)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8136756e)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8136f9f5)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81371c47)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/symlink.c (ffffffff81373ae7)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8137401a)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81374590)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81387f04)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813881ee)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81391d91)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813998a2)
Location: include/linux/uaccess.h:174
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
In security/tomoyo/domain.c (ffffffff813f7b1f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814279d4)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81429861)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In crypto/ahash.c (ffffffff8142bd9d)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8142d374)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81446e23)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
```
```
In block/bounce.c (ffffffff8146f8d3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8148175a)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff81483117)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff8148f34b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81494413)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/swiotlb.c (0)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff815baf88)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816111b6)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8166e0ed)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8167442f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2209)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff816c602c)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff816e7650)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff817bda94)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
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
In drivers/md/dm.c (ffffffff817be676)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff817ce86f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8182fa10)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff81984fc4)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819853bb)
Location: include/linux/uaccess.h:174
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
In arch/x86/events/core.c (ffffffff810081a6)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81040120)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81082d19)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (ffffffff810ec2d0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In kernel/futex.c (ffffffff8112b4bf)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff81136d4f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166fc2)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6199)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811e6415)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In mm/maccess.c (ffffffff811f419b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff811f84fe)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff8120423f)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8120f3f7)
Location: include/linux/uaccess.h:174
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
In mm/memory.c (ffffffff81231b01)
Location: include/linux/uaccess.h:174
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
In mm/vmalloc.c (ffffffff81243bd5)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff812498da)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff8124fd3b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812627f4)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81262b30)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8126da45)
Location: include/linux/uaccess.h:174
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
In mm/huge_memory.c (ffffffff81273968)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127b858)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zsmalloc.c (ffffffff8128e949)
Location: include/linux/uaccess.h:174
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812903ae)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812980d5)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/exec.c (ffffffff812a1a53)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/libfs.c (ffffffff812c6d49)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812d841c)
Location: include/linux/uaccess.h:174
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
In fs/direct-io.c (ffffffff812e007b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e2cd3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff812f488b)
Location: include/linux/uaccess.h:174
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
In fs/dax.c (ffffffff812f9571)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/iomap.c (ffffffff8130eca3)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8134d53d)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81353059)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813683a6)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370a61)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81370f63)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8139441a)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395e07)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8139df10)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813a0204)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813a251e)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813a2dcb)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813a2fa0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6a49)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813b703b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813c0dca)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813c8495)
Location: include/linux/uaccess.h:174
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
In security/tomoyo/domain.c (ffffffff81428aef)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8145a834)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8145c978)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:174
Inline: True
```
```
In crypto/ahash.c (ffffffff8145ea64)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8145ffe0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81479f56)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814a3ca3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814b621e)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-zoned.c (ffffffff814b7d6c)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones
```
```
In lib/scatterlist.c (ffffffff814c3f5b)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff814c9853)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/balloon.c (ffffffff815f3638)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8164ac36)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816a9bce)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816b05da)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ee4a9)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd_dif.c (ffffffff817025b6)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/ata/libata-sff.c (ffffffff81723d90)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81805a96)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_create
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
In drivers/md/dm.c (ffffffff81806985)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/edac/edac_mc.c (ffffffff818174e0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8187a1d0)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff819e14b3)
Location: include/linux/uaccess.h:174
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e190b)
Location: include/linux/uaccess.h:174
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
In arch/x86/events/core.c (ffffffff81008086)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416e0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810898c9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In kernel/power/snapshot.c (ffffffff810f7970)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff81134fb7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff811423af)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173d22)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811e089f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff811f6f65)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff8120652b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page_alloc.c (ffffffff8120a8f5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/truncate.c (ffffffff81216bff)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81221c29)
Location: include/linux/uaccess.h:171
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
In mm/memory.c (ffffffff812452d1)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff812582d5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/swapfile.c (ffffffff8125df07)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812642ab)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81277074)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812773b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8128204b)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff81287f0b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8128fbff)
Location: include/linux/uaccess.h:171
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
In mm/zsmalloc.c (ffffffff812a2ae9)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812a5342)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812ad35a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812b6813)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff812dbf19)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff812ed8ec)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff812f4ba7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f7935)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81309738)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff8130d741)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/iomap.c (ffffffff8132441a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_end
  - fs/iomap.c:iomap_read_page_sync
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813656cd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8136b186)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81380829)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388ef6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81389405)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813ad16a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeb5d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813b6c80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813b8f85)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813bb2fe)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813bbc0c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813bbda0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813cff99)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813d058b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff813da12a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff813e16b7)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff813e9e20)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814453bf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814783a4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81479fe8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff8147c40f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8147da70)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81497d6a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814be532)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814c9b1e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff814cb0dd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/scatterlist.c (ffffffff814d8636)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff814de867)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff8160cd43)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e6b7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81668ef6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816ca80e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816d07a7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712049)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817231cd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff817466b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81831c99)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
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
In drivers/edac/edac_mc.c (ffffffff81842d80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8189ade0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c463)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c8cb)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff81008377)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f317)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043be0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108cddf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff810fff18)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff8113e3d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8114d7c5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180b14)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811f64a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8120f0e1)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff8121da8e)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff812265b3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81231492)
Location: include/linux/uaccess.h:171
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
```
```
In mm/memory.c (ffffffff81257311)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff81268c56)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8126d4f8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812790c4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff8127f203)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812928d2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:memcmp_pages
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81292cec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8129e169)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff812a2b27)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812aac98)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zsmalloc.c (ffffffff812be032)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812c0af3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c9cd4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812d36fc)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff812fa5c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130f0b1)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff81315f5f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81317f80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8132b8d5)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff8133595a)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8134c558)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8138ea10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813946a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a964a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2ffa)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b35d6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff813d741f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d903f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e1360)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e3d97)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e5bb2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e64a2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e6640)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fab87)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb1a8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8140625d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff8140d38a)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff81415f9c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8147303b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a61e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814a7eb0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814aa706)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814abd0a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c589c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff814eccc3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814f81ef)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff814f9a2e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/scatterlist.c (ffffffff81504699)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8150a40d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff816419e6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8164243c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8169e862)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81705dc8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8170a499)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174d9e9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8176061c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8178237d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff81874432)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81885b78)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff818e5160)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c114)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c4fe)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff8100858f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f999)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044330)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108da3f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff8110c378)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff81149f68)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff811594d5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c984)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff81203461)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff8121c3c9)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff8122b52e)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff8123441f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8123f552)
Location: include/linux/uaccess.h:171
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
```
```
In mm/util.c (ffffffff81245c67)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff812658a1)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff8127758e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8127c038)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff81288ba4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff8128ec63)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812a2655)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a2a6c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812ada19)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff812b401a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bc269)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812cff22)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812d28a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812db7b2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812e528c)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff8130c340)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81323c39)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff81328ddf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132adf6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8133e725)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff8134955a)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffff81351102)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff81364828)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813a7470)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ad023)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c256a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cc07c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813cc7d6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813eed47)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813f1451)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3038)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813fb3b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813fddd9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813ffc02)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff81400518)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff814006c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81414a57)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81415078)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81420dbd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81428791)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff8142fe80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148cddb)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814c0e74)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814c2b10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814c53c6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814c69ea)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814dea9c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff81506110)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81515fcf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff815177b9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81522b92)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81528547)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81662ff6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81664a05)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816c1912)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8172a018)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8172e799)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81771b99)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff817845ad)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff817a602d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818a6242)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818b7b18)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff819172f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac33d4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac37be)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff81009622)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042ce5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047d86)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811171a7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff8115a9eb)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffffffff8116a5aa)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a1353)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff8122b1de)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/events/core.c (ffffffff81231e5d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81246ede)
Location: include/linux/uaccess.h:171
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
In kernel/watch_queue.c (ffffffff8124cb06)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In mm/maccess.c (ffffffff8125842c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff812619ec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8126cd94)
Location: include/linux/uaccess.h:171
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
In mm/util.c (ffffffff812739e7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81295bf9)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff812a748b)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In mm/page_alloc.c (ffffffff812ae36b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812bb845)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812c1a03)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812d6d76)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812d7278)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:poison_pages
```
```
In mm/migrate.c (ffffffff812e2ef6)
Location: include/linux/uaccess.h:171
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
In mm/khugepaged.c (ffffffff812f17a1)
Location: include/linux/uaccess.h:171
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
In mm/zsmalloc.c (ffffffff8130707e)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff813082ee)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffffffff8131175e)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/exec.c (ffffffff8131c400)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81345826)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8135cab4)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff81362e82)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81364862)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813783d1)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff8138e8cd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff81397b72)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813acae6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_write_end_inline
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813f3610)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813f9377)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8140ec7a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff814181a5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff81418b38)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8143c33d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff8143c978)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81440914)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff81448b27)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8144b837)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8144d5c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8144def7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8144e070)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81462d16)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81463338)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8146fe47)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8147645d)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff8147fdee)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff814e4052)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8152171e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff815242fc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff81525cb3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8153e468)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff81566cb1)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81576966)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81577f76)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81585bd2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff815883d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In arch/x86/lib/usercopy.c (ffffffff815ff915)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ffcbe)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff8171352a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714585)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81774e94)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817e809e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817eecb1)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff818343d9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8184439d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8186a307)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff819762c4)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81987d7f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In net/core/skbuff.c (ffffffff819eaa70)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810086d2)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042c7d)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104723c)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066295)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066e41)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067fe4)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff81087300)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff8111224c)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In kernel/futex.c (ffffffff811575ec)
Location: include/linux/uaccess.h:232
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
In kernel/kexec_core.c (ffffffff81166cea)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e4a3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff81233114)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In kernel/events/core.c (ffffffff8123bacd)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81251539)
Location: include/linux/uaccess.h:232
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
In kernel/watch_queue.c (ffffffff81256f46)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In mm/maccess.c (ffffffff81262bcf)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff8126adbc)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In mm/shmem.c (ffffffff8127783a)
Location: include/linux/uaccess.h:232
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
In mm/util.c (ffffffff8127e277)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff812a0ba4)
Location: include/linux/uaccess.h:232
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
In mm/vmalloc.c (ffffffff812b270b)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b9f84)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812c72e5)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812cd65f)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff812e2906)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812e2da0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812ee336)
Location: include/linux/uaccess.h:232
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
In mm/khugepaged.c (ffffffff812fdcf6)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff81312dbe)
Location: include/linux/uaccess.h:232
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:init_zspage
```
```
In mm/userfaultfd.c (ffffffff81314088)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff813278e0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81352007)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff81366ade)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/buffer.c (ffffffff81367666)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3dd)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/mpage.c (ffffffff813712e0)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/aio.c (ffffffff813860d8)
Location: include/linux/uaccess.h:232
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
In fs/dax.c (ffffffff813a002b)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff813a93f2)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813bca6f)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end_inline
```
```
In fs/ext4/inline.c (ffffffff81405da0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81408475)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d4d)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142af00)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c6f7)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff8145868d)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffff81458cf8)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff8145cb41)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/journal.c (ffffffff8146571c)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81467f17)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81469c00)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146a4ae)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146a610)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e5c3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8147eb88)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8148a6e4)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81490ec4)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8149b4ce)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In security/tomoyo/domain.c (ffffffff8150147b)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8153e58e)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In crypto/ahash.c (ffffffff81541175)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff81542be3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8155ae64)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bounce.c (ffffffff81581b19)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8159332e)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81594bf8)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a2cb2)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff815a8084)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
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
In arch/x86/lib/usercopy.c (ffffffff81624845)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624bae)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff8173041a)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730c65)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff8178fbe4)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817fcffe)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff818035b1)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81844d59)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff818546b6)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff81879117)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8197b2b4)
Location: include/linux/uaccess.h:232
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8198bcaf)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff819bee18)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff819ea7b0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009087)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044659)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048dd6)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810666ec)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810673ed)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106854f)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff81087f30)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81113ff3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In kernel/futex.c (ffffffff81158a3c)
Location: include/linux/uaccess.h:232
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
In kernel/kexec_core.c (ffffffff81167a84)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f1c1)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff8124017d)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff8125783f)
Location: include/linux/uaccess.h:232
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
In kernel/watch_queue.c (ffffffff8125b3d6)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In mm/maccess.c (ffffffff812675ef)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff8126ff6f)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In mm/shmem.c (ffffffff8127c69a)
Location: include/linux/uaccess.h:232
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
In mm/util.c (ffffffff812833e7)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff812a64e4)
Location: include/linux/uaccess.h:232
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
In mm/vmalloc.c (ffffffff812bd8da)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff812bf427)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff812cdc05)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812d40de)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff812ea096)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812ea514)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812f4458)
Location: include/linux/uaccess.h:232
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
In mm/khugepaged.c (ffffffff81304e6c)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff81318087)
Location: include/linux/uaccess.h:232
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff8131a230)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8132d75d)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff81358d17)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff8136d38e)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/buffer.c (ffffffff8136e0a9)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/direct-io.c (ffffffff81375c8f)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/mpage.c (ffffffff81377c93)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/aio.c (ffffffff8138d228)
Location: include/linux/uaccess.h:232
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
In fs/dax.c (ffffffff813a75c1)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/verity/verify.c (ffffffff813b0924)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff813c4ade)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/ext4/inline.c (ffffffff8140c0e0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140e789)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142854f)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a73)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814333c6)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81460435)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621d8)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8146aebc)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8146d51a)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8146f2fc)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8146fbb3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8146fcd0)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81484097)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81484715)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814901b3)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8149bc74)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814a06de)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814a1b49)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/tomoyo/domain.c (ffffffff81507f5b)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81546c5b)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:232
Inline: True
```
```
In crypto/ahash.c (ffffffff815497a5)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8154b285)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff81563696)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
```
```
In block/bio-integrity.c (ffffffff8159a130)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8159b9bb)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815a9be2)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff815b350a)
Location: include/linux/uaccess.h:232
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
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
```
In lib/buildid.c (ffffffff815eff19)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81608235)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8160855e)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff81713fba)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817147f1)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81772754)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff817e1a88)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7d77)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81827ee9)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81838256)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8185b957)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/md/md-bitmap.c (ffffffff8195f4d1)
Location: include/linux/uaccess.h:232
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81970ad5)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff819a3517)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff819d0d70)
Location: include/linux/uaccess.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009f77)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a635)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f7c6)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810708b5)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071773)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072a0d)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff810972b0)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811340f4)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In kernel/futex.c (ffffffff8117d92c)
Location: include/linux/uaccess.h:222
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
In kernel/kexec_core.c (ffffffff8118d316)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9041)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff8127ab45)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812910dc)
Location: include/linux/uaccess.h:222
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
In kernel/watch_queue.c (ffffffff812971e4)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In mm/maccess.c (ffffffff812a402f)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/truncate.c (ffffffff812ad39a)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In mm/shmem.c (ffffffff812ba8aa)
Location: include/linux/uaccess.h:222
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
In mm/util.c (ffffffff812c15a7)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
  - mm/util.c:copy_huge_page
  - mm/util.c:copy_huge_page
```
```
In mm/memory.c (ffffffff812e79a4)
Location: include/linux/uaccess.h:222
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
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/vmalloc.c (ffffffff813000c7)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8130159a)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In mm/swapfile.c (ffffffff81313085)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81319da8)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff81331fb8)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81332434)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/migrate.c (ffffffff8133e7c6)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8134ebff)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff8136458e)
Location: include/linux/uaccess.h:222
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/secretmem.c (ffffffff813663b0)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_freepage
```
```
In mm/userfaultfd.c (ffffffff81367169)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff8137af8d)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/libfs.c (ffffffff813a7377)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/remap_range.c (ffffffff813bc06e)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/buffer.c (ffffffff813bce32)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/direct-io.c (ffffffff813c20f2)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/mpage.c (ffffffff813c434d)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/aio.c (ffffffff813da988)
Location: include/linux/uaccess.h:222
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
In fs/dax.c (ffffffff813f4da3)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/verify.c (ffffffff81400504)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff81412252)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145efe0)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81461681)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c282)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff814852bd)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8148654d)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff814b58b8)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b76ce)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814c16cc)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff814c3db2)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff814c5cec)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff814c65d6)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff814c6740)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814db351)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbd95)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff814e7bdf)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff814f366a)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff814f85af)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In fs/fuse/ioctl.c (ffffffff814f9c23)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In security/tomoyo/domain.c (ffffffff81565199)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff815a743b)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In crypto/ahash.c (ffffffff815a9f85)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff815aba65)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff815c6d0a)
Location: include/linux/uaccess.h:222
Inline: True
```
```
In lib/scatterlist.c (ffffffff8161291d)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81614f01)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/buildid.c (ffffffff8165d1b9)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e75)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8167719e)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/xen/grant-table.c (ffffffff817909f5)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81791631)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff817f7f84)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8186d778)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81873c9c)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b3849)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff818c5190)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff818eb3bc)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In drivers/md/md-bitmap.c (ffffffff81a04e20)
Location: include/linux/uaccess.h:222
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81a193f5)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/firmware/efi/capsule.c (ffffffff81a50797)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81a80660)
Location: include/linux/uaccess.h:222
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810096ce)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054a74)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105ab02)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dea3)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f7d7)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080d8f)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/mm/fault.c (ffffffff810a9de9)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In kernel/futex/core.c (ffffffff811b3163)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811b675d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcb3f)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff812cdb26)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e65cd)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff812ed00c)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In mm/maccess.c (ffffffff812fc0ef)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff8131cbea)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff8131e5b5)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81348b63)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff813629ca)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In mm/swapfile.c (ffffffff8137e357)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff8138569f)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff8139e473)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813a385a)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff813e2523)
Location: include/linux/uaccess.h:182
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff813e4752)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffffffff813fb24d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:copy_string_kernel
```
```
In fs/aio.c (ffffffff81465390)
Location: include/linux/uaccess.h:182
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
In fs/dax.c (ffffffff8146797d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/verity/verify.c (ffffffff8147443b)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/ext4/inline.c (ffffffff814dd7f4)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff8153d4c2)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81540ea0)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8154c05d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8154eb24)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550c3a)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff81551703)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8155190c)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81568bd5)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81569a1d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff8160099d)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff8164e791)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In crypto/ahash.c (ffffffff81651d44)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8165337c)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff816df4b4)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff816e2e5b)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/buildid.c (ffffffff81776613)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff81791e1a)
Location: include/linux/uaccess.h:182
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff817921d5)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/char/virtio_console.c (ffffffff81936579)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb6db)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a003c5)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bd33)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81b6cb17)
Location: include/linux/uaccess.h:182
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
In drivers/edac/edac_mc.c (ffffffff81b82041)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf66c)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81bf5f3c)
Location: include/linux/uaccess.h:182
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff8100ab6f)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810625c5)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810688d2)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810c33b9)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f4063)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811f78ad)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244267)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (ffffffff813390e5)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813500aa)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff8135738c)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In mm/maccess.c (ffffffff8136633f)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff81390682)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff81392095)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff813c0fd0)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff813de38a)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In mm/swapfile.c (ffffffff813fbf67)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81403408)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff8141db93)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81423645)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff81468331)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:restore_freelist
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff8146c73c)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/aio.c (ffffffff814f53d0)
Location: include/linux/uaccess.h:191
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
In fs/dax.c (ffffffff814f803d)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/ext4/inline.c (ffffffff81576824)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff815dbcf1)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff815dfff3)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff815ebe2d)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff815ef5a5)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1916)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c505)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d650)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff816b1904)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff81707bf1)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In crypto/ahash.c (ffffffff8170b774)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8170d09c)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff817cf6f4)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff817d557b)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81a963b9)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30c2b)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e9d5)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1183)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81d08c27)
Location: include/linux/uaccess.h:191
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d20864)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63e8c)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81da485c)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff8201f060)
Location: include/linux/uaccess.h:191
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fc3d)
Location: include/linux/uaccess.h:191
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ffa5)
Location: include/linux/uaccess.h:191
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
In arch/x86/events/core.c (ffffffff8100a386)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81064092)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106a1bb)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810c6ad9)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In kernel/futex/core.c (ffffffff812087f3)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8120c33d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b347)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_events_user.c (ffffffff812c3b0e)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/events/core.c (ffffffff8136a6e8)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81381283)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff81388c13)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In mm/maccess.c (ffffffff813987df)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff813c2fd5)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff813c4a95)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff813f5d5c)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/swapfile.c (ffffffff8142f077)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff814368cf)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff814525f3)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff814588e5)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/zsmalloc.c (ffffffff8149e1b1)
Location: include/linux/uaccess.h:213
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff814a144a)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff8152f23d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/jbd2/transaction.c (ffffffff816137af)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff8161730f)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff8162390d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81627585)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629a06)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/ecryptfs/mmap.c (ffffffff816443f5)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8164550f)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In security/tomoyo/domain.c (ffffffff816ea307)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In lib/scatterlist.c (ffffffff8180dba4)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81813fa1)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81ae1bc9)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81b842eb)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd2805)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c18c63)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/md/md-bitmap.c (ffffffff81d71d9a)
Location: include/linux/uaccess.h:213
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81d89a61)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcefdc)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81e133fc)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff8209f073)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce16a)
Location: include/linux/uaccess.h:213
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
In arch/x86/events/core.c (ffffffff8100faa6)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b5aa)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8107168b)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/fault.c (ffffffff810cef59)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121f683)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_get_value_locked
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8122363d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127524b)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/trace_events_user.c (ffffffff812e035e)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In kernel/events/core.c (ffffffff81393078)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813aa633)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/watch_queue.c (ffffffff813b2673)
Location: include/linux/uaccess.h:213
Inline: True
```
```
In mm/maccess.c (ffffffff813c25df)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:strncpy_from_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
  - mm/maccess.c:copy_to_kernel_nofault
```
```
In mm/shmem.c (ffffffff813edb1d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81421a39)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/memory.c:copy_folio_from_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/zsmalloc.c (ffffffff814cd2d4)
Location: include/linux/uaccess.h:213
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff814d0bdd)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff8156411d)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/squashfs/file.c (ffffffff816606e5)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662c56)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In security/tomoyo/domain.c (ffffffff81727017)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In lib/scatterlist.c (ffffffff81853854)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff818583af)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In drivers/char/virtio_console.c (ffffffff81b34fb9)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd821b)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27475)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d9b3)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c812b6)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
```
```
In drivers/md/md-bitmap.c (ffffffff81e28e6d)
Location: include/linux/uaccess.h:213
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
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81e411f2)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87d0c)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In net/core/skbuff.c (ffffffff81ed05bc)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In lib/buildid.c (ffffffff82177073)
Location: include/linux/uaccess.h:213
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In arch/x86/lib/usercopy.c (ffffffff821a899a)
Location: include/linux/uaccess.h:213
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
In arch/arm64/kernel/perf_callchain.c (ffff8000100a360c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm64/kernel/probes/uprobes.c (ffff8000100ac788)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol
```
```
In virt/kvm/kvm_main.c (ffff8000100bde80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_unmap_gfn
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffff8000101bb68c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (ffff8000101c8a04)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/debug/kdb/kdb_support.c (ffff800010203ca8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffff80001028bbf0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff8000102984b8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (ffff8000102a5968)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffff8000102b9fd0)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffff8000102c4a48)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffff8000102d0d5c)
Location: include/linux/uaccess.h:171
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
In mm/util.c (ffff8000102d9368)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffff8000102fc2d4)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffff80001030dac4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffff8000103135d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffff800010323b5c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffff80001032b97c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffff800010342038)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffff800010342b14)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffff80001034fa10)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffff8000103556b4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035d3ec)
Location: include/linux/uaccess.h:171
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
In mm/zsmalloc.c (ffff8000103748d8)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffff8000103782a8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/read_write.c (ffff8000103806a4)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/exec.c (ffff80001038c368)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffff8000103c0b50)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffff8000103dcfd0)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffff8000103e42d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e645c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffff8000103fdddc)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffff80001040a1c4)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffff800010413164)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffff80001042b348)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffff80001047acf0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff8000104818d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff800010499f68)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a40dc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffff8000104a4c54)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffff8000104c8128)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104cb400)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce6b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffff8000104d89ec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffff8000104dbe6c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffff8000104ddc3c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffff8000104de4d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffff8000104de778)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffff8000104f6204)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffff8000104f668c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff800010503a70)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffff80001050aba0)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffff800010514884)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffff80001058028c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffff8000105bb0d4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffff8000105bd2d4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffff8000105bfff0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffff8000105c1e50)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffff8000105dae0c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (ffff80001061d3c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffff80001061ec98)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffff80001062c04c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffff800010632bec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffff80001082cd34)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffff80001082e794)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffff8000108b2bd4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffff800010920ca8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffff8000109256b8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffff800010975320)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffff80001098ad7c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffff8000109b2360)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffff800010afb174)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffff800010b0fe84)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffff800010bb0750)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/arm/kernel/perf_callchain.c (c0317d10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm/mm/highmem.c (c0321a80)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:__kunmap_atomic
```
```
In kernel/futex.c (c0400518)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/events/core.c (c04cebdc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/uprobes.c (c04d7004)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (c04e60e8)
Location: include/linux/uaccess.h:171
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
In arch/powerpc/kernel/traps.c (c00000000002e834)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:handle_hmi_exception
```
```
In arch/powerpc/mm/fault.c (c000000000086c10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/mm/hugetlbpage.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In arch/powerpc/lib/vmx-helper.c (c0000000000b4184)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/powerpc/lib/vmx-helper.c:exit_vmx_usercopy
```
```
In arch/powerpc/perf/callchain.c (c0000000001251dc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_64
  - arch/powerpc/perf/callchain.c:read_user_stack_64
```
```
In arch/powerpc/perf/core-book3s.c (c0000000001290d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (c00000000021cb14)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/kexec_core.c (c000000000231324)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e4f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (c000000000337c34)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c00000000034289c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (c00000000035b500)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (c000000000371fbc)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (c00000000037f1ec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (c000000000390fe8)
Location: include/linux/uaccess.h:171
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
In mm/util.c (c000000000398f78)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (c0000000003c7a74)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (c0000000003de6a0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (c0000000003e52d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (c0000000003f8910)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (c0000000004027fc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (c00000000041f894)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (c00000000041ff8c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (c000000000432430)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (c00000000043ccf0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000448ed8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (c0000000004680d0)
Location: include/linux/uaccess.h:171
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
```
```
In mm/userfaultfd.c (c00000000046b100)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (c000000000477280)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (c000000000484cd0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (c0000000004bf31c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (c0000000004e2744)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (c0000000004ea3ec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec6b8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (c000000000507358)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (c0000000005161cc)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (c000000000520ed0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (c00000000053bc74)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (c00000000059dda8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a61b8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c429c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d12e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (c0000000005d1df0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (c000000000600904)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c0000000006044c8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607128)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (c00000000061395c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (c000000000617128)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (c0000000006197b8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (c00000000061a3f4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (c00000000061a5d4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (c0000000006370c8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (c000000000637604)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c00000000064874c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (c000000000652f40)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (c00000000065cd14)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (c0000000006edbc0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (c0000000007417d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (c000000000744384)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (c000000000747f20)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (c00000000074a4a0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (c00000000076be30)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (c0000000007bbe54)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (c0000000007be260)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (c0000000007ce8a4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (c0000000007d630c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (c00000000094cec0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (c0000000009c4bac)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/scsi/scsi_lib.c (c000000000a2f0a8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (c000000000a4b808)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (c000000000a7af10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (c000000000be9318)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (c000000000c03418)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (c000000000c86544)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffe00013eab2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf6e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffe0001ce9d2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In mm/maccess.c (ffffffe0001dd2d8)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffe0001e52c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffe0001edee0)
Location: include/linux/uaccess.h:171
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
In mm/util.c (ffffffe0001f3700)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffe00020b808)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffe0002167e2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffe00021a880)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffe000224404)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffe00022a5b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffe0002362fe)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffe000236740)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffe00023e870)
Location: include/linux/uaccess.h:171
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
In mm/zsmalloc.c (ffffffe00024d72c)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/userfaultfd.c (ffffffe00024ffc4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffe000255ce6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffe00025db3c)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffe0002810c0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffe00029514e)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffe00029a0ea)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b76e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffe0002abf40)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffe0002b3c94)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffe0002bad16)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffe0002c89c4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffe0003053da)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030a494)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031d6b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe0003255b4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffe000325d28)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffe000341e16)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffe00034422e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000346038)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffe00034e4ce)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffe000350aee)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffe0003526e0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffe000352e2c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffe000352fd0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffe000365014)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffe0003653d2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffe000370866)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffe0003772e0)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffe00037e464)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffe0003d0f08)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffe000400c06)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffe000402a50)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffe00040500a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffe0004069b2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffe00041eb54)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bio-integrity.c (ffffffe000450224)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffe000451cc8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffe00045c254)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffe000461074)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (ffffffe00056587e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffe00059f5a2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dd940)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffe0005ef18a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffe00060ef5e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec98e)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf76)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffe000741786)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
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
In arch/x86/events/core.c (ffffffff8100858f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fb19)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810444b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c9ff)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff81104598)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff81142588)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff81151af5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184fa4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811fba81)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81214a19)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff81223b7e)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff8122ca6f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81237ba2)
Location: include/linux/uaccess.h:171
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
```
```
In mm/util.c (ffffffff8123e2b7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8125def1)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff8126fbde)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81274688)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff81281184)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81287243)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8129ac35)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8129b04c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812a5ff9)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff812ac5fa)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b4849)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812c8502)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812cae83)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d3d92)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812dd86c)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff81304920)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8131c219)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff813213bf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff813233d6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff81336d05)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff81341b3a)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffff813496e2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8135ce08)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139fa50)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a5603)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813bab4a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c465c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c4db6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e7327)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e9a31)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb618)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f3990)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f63b9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f81e2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f8af8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f8ca0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d037)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d658)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141939d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81420d71)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff81428460)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff814853bb)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b9454)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814bb0f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814bd9a6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814befca)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d707c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814fe6f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150e5af)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8150fd99)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8151b172)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81520b27)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81628e66)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a875)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff81687362)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816efdf8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4789)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81726289)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81738c9d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8176b0ed)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8184c0c2)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff8185d998)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff818b72f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a62224)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a6260e)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff81006d7f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f319)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033ad0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b52f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff810f5838)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff811358e8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff81144dd5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811780e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811ee7cc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81207789)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff81216d2e)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff8121fb4f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8122abe2)
Location: include/linux/uaccess.h:171
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
```
```
In mm/util.c (ffffffff812312b7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff81250341)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff81261b4e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff812665f8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff81272ff4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812790a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff8128c7f5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff8128cc0c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff81297aa9)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff8129e6a7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a58b1)
Location: include/linux/uaccess.h:171
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
In mm/zsmalloc.c (ffffffff812b9542)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812bbde6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812c4a12)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ce4ec)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff812f5540)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8130cdb9)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff81311f5f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81313f76)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff8132767b)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff813324cf)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffff8133a3c2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8134daa8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813904e0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81396093)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ab5da)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b50dc)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813b5836)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813d7da7)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813da4b1)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc098)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813e4410)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813e6e39)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813e8c62)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813e9578)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813e9720)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdab7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe0d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff81409e1d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff814117f1)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff81418ee0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81475ddb)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814a9e74)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814abb10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814ae3c6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814af9ea)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814c7a3c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814eec00)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814fe9df)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff815000b9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff8150b462)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff81510e17)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/char/virtio_console.c (ffffffff81664f52)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff816c9f08)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb74a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
  - drivers/nvdimm/pmem.c:write_pmem
```
```
In drivers/nvdimm/btt.c (ffffffff816ed158)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_write_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_read_pg
  - drivers/nvdimm/btt.c:btt_rw_integrity
```
```
In drivers/nvdimm/blk.c (ffffffff816ef3af)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ff6b9)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8171a93d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8174af4d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818136e2)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff81824f68)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff81871240)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f294)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f67e)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff8100854f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f959)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c9af)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff81102848)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff81140438)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8114f9a5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182d74)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff811f9851)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff812127b9)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff8122191e)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff8122a80f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81235942)
Location: include/linux/uaccess.h:171
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
```
```
In mm/util.c (ffffffff8123c057)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8125bc91)
Location: include/linux/uaccess.h:171
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
In mm/vmalloc.c (ffffffff8126d97e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff81272428)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8127ef94)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff81285053)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff81298a45)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81298e5c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812a3e09)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff812aa40a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b2659)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812c6312)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812c8c93)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812d1ba2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812db67c)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff81302710)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff81319ce9)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff8131ee8f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81320ea6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813347d5)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff8133f60a)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffff813471b2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8135a8d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff8139d2b0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a2e63)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b83aa)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c1aec)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813c2246)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813e46a7)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813e6db1)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e8998)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff813f0d10)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff813f3739)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff813f5562)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff813f5e78)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff813f6020)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a3b7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8140a9d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8141553d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff8141cf11)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff81424600)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff8148145b)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814b54e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814b7180)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814b9a36)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814bb05a)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814d310c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff814fa780)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150a63f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff8150be29)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff81517202)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8151cbb7)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff81656e36)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81658845)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816b56a2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff8171d4d8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff81721c59)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765059)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff8177942d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff8179aead)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff8189b6f2)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818acfc8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff819082f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace614)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace9fe)
Location: include/linux/uaccess.h:171
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
In arch/x86/events/core.c (ffffffff810086af)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040c68)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456f0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108ed1f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_unmap_tables
```
```
In kernel/power/snapshot.c (ffffffff8110dc2f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In kernel/futex.c (ffffffff8114cf68)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:arch_futex_atomic_op_inuser
```
```
In kernel/kexec_core.c (ffffffff8115c7e4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811906a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/stackmap.c (ffffffff812082f8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/uprobes.c (ffffffff81221739)
Location: include/linux/uaccess.h:171
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
In mm/maccess.c (ffffffff81230ade)
Location: include/linux/uaccess.h:171
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
In mm/truncate.c (ffffffff81239bee)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff81245c08)
Location: include/linux/uaccess.h:171
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
```
```
In mm/util.c (ffffffff8124b785)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/memory.c (ffffffff8126b6c5)
Location: include/linux/uaccess.h:171
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
```
```
In mm/vmalloc.c (ffffffff8127d310)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
```
```
In mm/page_alloc.c (ffffffff8128226e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8128de93)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
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
In mm/zswap.c (ffffffff812950dd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/ksm.c (ffffffff812a8803)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a8c47)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/migrate.c (ffffffff812b46cb)
Location: include/linux/uaccess.h:171
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
In mm/huge_memory.c (ffffffff812ba6ef)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c2cff)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/zsmalloc.c (ffffffff812d7b83)
Location: include/linux/uaccess.h:171
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
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/userfaultfd.c (ffffffff812d9983)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/read_write.c (ffffffff812e29da)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/exec.c (ffffffff812ec603)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/libfs.c (ffffffff81313d37)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/buffer.c (ffffffff8132b98f)
Location: include/linux/uaccess.h:171
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
In fs/direct-io.c (ffffffff81330b96)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332bcd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/aio.c (ffffffff813469dd)
Location: include/linux/uaccess.h:171
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
In fs/dax.c (ffffffff81352fb6)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/verity/verify.c (ffffffff8135a499)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/iomap/buffered-io.c (ffffffff8136e02f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inline.c (ffffffff813b180f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b7536)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813cd0b1)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6c53)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/readpage.c (ffffffff813d73c6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/verity.c (ffffffff813f9ab7)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fc39c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe1e8)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/journal.c (ffffffff814067ef)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff81409350)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b192)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b994)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8140bc0c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_finish_page
  - fs/squashfs/page_actor.c:direct_next_page
```
```
In fs/ecryptfs/mmap.c (ffffffff814200ae)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff814206a3)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142c2b4)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81433cf5)
Location: include/linux/uaccess.h:171
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
In fs/fuse/readdir.c (ffffffff8143b729)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In security/tomoyo/domain.c (ffffffff81498fd2)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In crypto/scatterwalk.c (ffffffff814cdf6f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfc28)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: include/linux/uaccess.h:171
Inline: True
```
```
In crypto/ahash.c (ffffffff814d24dd)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff814d3b15)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814ebb1d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/bounce.c (ffffffff81513926)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81523cb6)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff815254d0)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/scatterlist.c (ffffffff815309cf)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In lib/iov_iter.c (ffffffff8153640e)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In drivers/xen/grant-table.c (ffffffff8167141d)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e4c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/char/virtio_console.c (ffffffff816d0139)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/block/loop.c (ffffffff81738846)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8173d030)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/scsi/scsi_lib.c (ffffffff817806f5)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg
```
```
In drivers/scsi/sd.c (ffffffff81793254)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-sff.c (ffffffff817b4d34)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/md/md-bitmap.c (ffffffff818b7889)
Location: include/linux/uaccess.h:171
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
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/edac/edac_mc.c (ffffffff818c921f)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In net/core/skbuff.c (ffffffff8192962c)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ts_finish
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In arch/x86/lib/usercopy.c (ffffffff81adab24)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaf15)
Location: include/linux/uaccess.h:171
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
