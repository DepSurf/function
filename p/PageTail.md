# Function: <code>PageTail</code>

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
In arch/x86/mm/gup.c (ffffffff8107156f)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In kernel/futex.c (ffffffff810ffb31)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8113c6ad)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811796c8)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811877c6)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118dd31)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page_alloc.c (ffffffff8119257a)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
```
```
In mm/page-writeback.c (ffffffff81199428)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8119d2cc)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
  - mm/swap.c:__get_page_tail
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a2371)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff811a8d6a)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/compaction.c (ffffffff811b5945)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811ba627)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811be0d8)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff811c2d86)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mmap.c (ffffffff811c4381)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/swap_state.c (ffffffff811d2723)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811d4597)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811daab1)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/sparse.c (ffffffff811e392f)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff811e470f)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/ksm.c:page_trans_compound_anon
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff811e8af1)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/slub.c:ksize
  - mm/slub.c:kfree
```
```
In mm/migrate.c (ffffffff811f0d0d)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f5e44)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811fa843)
Location: include/linux/page-flags.h:398
Inline: True
```
```
In mm/memory-failure.c (ffffffff81201722)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/pipe.c (ffffffff81214add)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812438fe)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/direct-io.c (ffffffff81249899)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
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
```
```
In fs/aio.c (ffffffff8125b691)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/proc/page.c (ffffffff812880e8)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
```
```
In fs/ext4/inode.c (ffffffff8129ac8b)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff812cdfe1)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff812eb16d)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8130eac9)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81316b27)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8134aa97)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In block/bio.c (ffffffff813b19f1)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_check_pages_dirty
```
```
In lib/iov_iter.c (ffffffff813fb680)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814736ab)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c37dc)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8151753a)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8151d7db)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff815c28dd)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/virtio_net.c (ffffffff815f2d40)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff815fc266)
Location: include/linux/page-flags.h:398
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8169b92f)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8170801f)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_shift
```
```
In net/ipv4/ip_output.c (ffffffff8175d618)
Location: include/linux/page-flags.h:398
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817692fd)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5cc5)
Location: include/linux/page-flags.h:398
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818076c4)
Location: include/linux/page-flags.h:398
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/futex.c (ffffffff81107800)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811a1cd5)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811a76f1)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811b2a17)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/truncate.c (ffffffff811b43de)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811b7e3b)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811bf66d)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff811c49c5)
Location: include/linux/page-flags.h:150
Inline: True
```
```
In mm/compaction.c (ffffffff811cfc33)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811d44b1)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811d4a99)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db3ab)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811df298)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff811e6b71)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff811eec70)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fc12e)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff811fecc6)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81202389)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81203f37)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/slub.c (ffffffff8120aeb9)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
```
```
In mm/migrate.c (ffffffff81212dfe)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8121843d)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121bf72)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81221249)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff81226a08)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/direct-io.c (ffffffff81272540)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812a46d8)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812b54a1)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81342d79)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff813f650c)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8110efcb)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811b1ae6)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811b7ae1)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811c3099)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/truncate.c (ffffffff811c4a6e)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811c849d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811cfd1b)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff811d4ad5)
Location: include/linux/page-flags.h:153
Inline: True
```
```
In mm/compaction.c (ffffffff811dfc74)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811e4506)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811e4ad1)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaf0f)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811ef0ac)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/page_vma_mapped.c (ffffffff811f6d7d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f7f11)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff811ff5a0)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120cbfa)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812104ff)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff812141c0)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81215f1d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8121cf04)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
```
```
In mm/migrate.c (ffffffff8122516e)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122a9da)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122d71e)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8123398d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff81238fd7)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff81283794)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81286060)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812ba038)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812cad02)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81358b98)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8140feec)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81110197)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811b7d3a)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bf913)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811cb530)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811ccd4a)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811d0eef)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811d945d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff811dd911)
Location: include/linux/page-flags.h:153
Inline: True
```
```
In mm/compaction.c (ffffffff811e997f)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811ee962)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811ef11c)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f6022)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff811f9e27)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/page_vma_mapped.c (ffffffff812021e9)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8120347b)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8120a25c)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8120c447)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/hugetlb.c (ffffffff8121853c)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8121aa2f)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8121f58c)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81223056)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81228fe4)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff8123090d)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812364c9)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81239fa4)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8123f23b)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff8124546c)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff81290dca)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812936aa)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812c786b)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d8192)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8136d5b1)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8141d86a)
Location: include/linux/page-flags.h:153
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8111b8e4)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811cc3a2)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811d4440)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811e08d1)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811e1fde)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff811e63e5)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811ee731)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff811f3391)
Location: include/linux/page-flags.h:154
Inline: True
```
```
In mm/compaction.c (ffffffff811ffccb)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81204dd2)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81206237)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120dc83)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81212277)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/page_vma_mapped.c (ffffffff8121ade9)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121bfbb)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff812234be)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff812261ef)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81229c72)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812333d0)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff81236997)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8123a7c2)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff8123e526)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81242eef)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff8124b6aa)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81254691)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8125975c)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8125eff1)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812653ee)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff812b3ad7)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b657e)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812eb47a)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fc892)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81391ff3)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff814486fa)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff811285ee)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811ed75e)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811f5e94)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff8120213f)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81203745)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81207981)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8120f3b1)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812145c1)
Location: include/linux/page-flags.h:149
Inline: True
```
```
In mm/compaction.c (ffffffff812210eb)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81225d15)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812264db)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e703)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8123328d)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81239451)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123cc39)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e049)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff81246332)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81247c73)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8124ae84)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812587ab)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81259967)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8125dd98)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81261bec)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81268902)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff8126e04d)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812784ea)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127d4b5)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81283114)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288d2b)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
```
In mm/memfd.c (ffffffff812944cf)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/block_dev.c (ffffffff812dc385)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812de115)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff813187b3)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a498)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813c1009)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8147930f)
Location: include/linux/page-flags.h:149
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81133ed0)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811fedbe)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81207b32)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff81214ac1)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81216015)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8121a505)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81221be3)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff81227493)
Location: include/linux/page-flags.h:150
Inline: True
```
```
In mm/compaction.c (ffffffff81234136)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff812393d9)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8123a839)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81242618)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81246a5e)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8124db66)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81251109)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812525dc)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff8125a754)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8125c247)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812609a8)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8126ce7f)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8126d579)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff81272627)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff8127648a)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8127d3a6)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff81282ebd)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128cb3e)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81291bfa)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81299166)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129dc7b)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
```
In mm/memfd.c (ffffffff812a923b)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/block_dev.c (ffffffff812f1ad7)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f37b7)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8132f6c5)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813417bb)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813da36b)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff81499a4c)
Location: include/linux/page-flags.h:150
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8113ec00)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff81219f3b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81223d71)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81225a15)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8122c8f5)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812314ee)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123720a)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff81243ec4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124a439)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124bb4c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81251407)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81258c63)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8125f9be)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812633e9)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126476a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8126dde1)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81275981)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81277422)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a189)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff81285a24)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81288a9d)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812916f5)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81298a6a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a0ffe)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a783e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812acb5b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b453b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b8e07)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff812c5628)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813570f0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81369bda)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81406025)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c7b3a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8114a882)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a7f6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff812278ab)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81231b01)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81233865)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123ab0d)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123f5ae)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124547a)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff81252384)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff812587de)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125a03c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125f9b7)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81267133)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8126e1ce)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81271b99)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81272fda)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff8127cc01)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81284951)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286f02)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81289c69)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812955fe)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8129860d)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a1475)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812a88c8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812ae977)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b8cde)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812be445)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c5e5b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812cbede)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff812d7016)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8136f6c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81381dfa)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81420ab4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814e0c3a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3177)
Location: include/linux/page-flags.h:181
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
In kernel/futex.c (ffffffff8115b3a4)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8124720e)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812541ea)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8125e6c1)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/truncate.c (ffffffff81260f8a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81269e75)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8126cdf3)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81272fca)
Location: include/linux/page-flags.h:189
Inline: True
```
```
In mm/compaction.c (ffffffff8128282f)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81287061)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81287dc3)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/memory.c (ffffffff8128fe6f)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff81297183)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8129e93a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a21c9)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a6b86)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812b4096)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812b6b4a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b9482)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812bcb9c)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812cb56a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/mempolicy.c (ffffffff812cc17d)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812d638a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812ddc29)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812e40b0)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ed892)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff812f229c)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff812fbb43)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff81302090)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff8130c151)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813b6f2a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813cc42a)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8146fac0)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8153fa8d)
Location: include/linux/page-flags.h:189
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff811574e6)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8125188a)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81be6a8a)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81268746)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8126b38a)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8127015e)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81277897)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff8127d66a)
Location: include/linux/page-flags.h:191
Inline: True
```
```
In mm/compaction.c (ffffffff8128c951)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81291310)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81292225)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129a8ef)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a2133)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812a9cf0)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812adaf9)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b2026)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812bfb22)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812c2d9b)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4e1a)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812c86cc)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d718a)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812d7a0d)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e1e9e)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812e6be0)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812efd43)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f930f)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff812fe753)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81307793)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130e997)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff81318011)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8138af92)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:headpage_already_acct
  - fs/io_uring.c:headpage_already_acct
```
```
In fs/proc/task_mmu.c (ffffffff813c85ca)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813de06e)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148a365)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8155c2ad)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81158901)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812556d6)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81bd8820)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8126e4e0)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8127047f)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81275f51)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127c6f7)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812827ea)
Location: include/linux/page-flags.h:191
Inline: True
```
```
In mm/compaction.c (ffffffff81291855)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81296840)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81297ee4)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129fdd0)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a79c3)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812af17b)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2fa1)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b76f6)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812c5282)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812c9c14)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812cbaba)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812cf07c)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812db653)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff812def33)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e9637)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812ee402)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812f56c4)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ff562)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff813053d3)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130df14)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81314d45)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff8131e212)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff81391736)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/proc/task_mmu.c (ffffffff813cf608)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813e4e5b)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148febb)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff81564b5d)
Location: include/linux/page-flags.h:191
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8117d808)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81291386)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81cb9e7a)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812ab4e8)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff812ae115)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812b25ce)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bf1db)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812c095a)
Location: include/linux/page-flags.h:205
Inline: True
```
```
In mm/compaction.c (ffffffff812d10e1)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff812d708d)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d82fa)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e33d6)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e8fe3)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/page_vma_mapped.c (ffffffff812f4b31)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f9e06)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_mlock
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff813097cf)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff8130ec34)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81310ba9)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8131461c)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff8132286d)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81326bc3)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81331573)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff8133429d)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff8133fcc5)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81349172)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff8134f223)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81358d73)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81360de5)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/io_uring.c (ffffffff813df635)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/proc/task_mmu.c (ffffffff814209e8)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81436a2b)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff814e7928)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff815c8edd)
Location: include/linux/page-flags.h:205
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex/core.c (ffffffff811b2a70)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/folio-compat.c (ffffffff81301325)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/vmscan.c (ffffffff8130f3a9)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff8133697b)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d98)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbe9)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff813a04f5)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff813da601)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/proc/page.c (ffffffff814b11c5)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff811f3910)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/folio-compat.c (ffffffff8136b9b5)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/vmscan.c (ffffffff8137ebcf)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/debug.c (ffffffff813adc11)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31d1)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d68a4)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff8141fd03)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff81460fc6)
Location: include/linux/page-flags.h:288
Inline: True
```
```
In fs/proc/page.c (ffffffff81547b85)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff81208097)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/folio-compat.c (ffffffff8139dc05)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/debug.c (ffffffff813e1fa2)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff814070f3)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140ba26)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:vma_address
```
```
In mm/page_alloc.c (ffffffff8141af6f)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/ksm.c (ffffffff81454917)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff81478273)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81497ae9)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/page_idle.c (ffffffff814a2a96)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/proc/page.c (ffffffff8157f7a4)
Location: include/linux/page-flags.h:282
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In mm/folio-compat.c (ffffffff813c78e5)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/folio-compat.c:isolate_lru_page
```
```
In mm/debug.c (ffffffff8140c7b8)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81433786)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff814382e6)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:vma_address
```
```
In mm/page_alloc.c (ffffffff81445d6f)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/ksm.c (ffffffff8148fb44)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff814a79b3)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff814c71e0)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
```
```
In mm/page_idle.c (ffffffff814d3926)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/proc/page.c (ffffffff815b81e1)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In virt/kvm/arm/mmu.c (ffff8000100cad34)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In kernel/futex.c (ffff8000101b7d24)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a5c44)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffff8000102aeeec)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c17ac)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/truncate.c (ffff8000102c3d40)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cba64)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d0dd0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffff8000102d83f4)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffff8000102eb004)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffff8000102f07bc)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffff8000102f1ab0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa118)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffff8000102fe36c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffff80001030559c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffff800010307694)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010308d20)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffff8000103147d0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffff80001031eb40)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff800010321940)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffff800010324ce0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffff8000103362ec)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff800010337254)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffff800010340d7c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff80001034a2cc)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffff800010352c38)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff8000103593cc)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035fdc4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffff800010368b64)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffff80001036f564)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffff80001037bff4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffff800010438e58)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffff800010450000)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffff8000105037c4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffff8000105dd778)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca070)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
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
In arch/arm/mm/flush.c (c031ec48)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In kernel/events/uprobes.c (c04d4e58)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04dab28)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c04ecb0c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c04f58b8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/util.c (c04ff714)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (c050e5c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0513d08)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0519210)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (c051ce94)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c0523640)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0527a78)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (c052ea9c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c05377e8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053c710)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0546c74)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (c054ec00)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/memcontrol.c (c05582c8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memfd.c (c0566d40)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c0601438)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/page.c (c061328c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c06bfe60)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c078abc0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In arch/powerpc/mm/mem.c (c0000000000874fc)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a65b8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In kernel/futex.c (c00000000021d31c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c000000000358ba8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c000000000362444)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c00000000037b57c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (c00000000037e194)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c000000000388c00)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c000000000390f10)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (c0000000003981d0)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (c0000000003ac450)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0000000003b5130)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0000000003b6180)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bf48c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (c0000000003c9b48)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c0000000003d2740)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0000000003d61c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d7f80)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (c0000000003e5f1c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c0000000003f3358)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f7098)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c0000000003fade4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (c000000000410bc8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000411c04)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (c00000000041e5cc)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (c000000000429210)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (c00000000043453c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000442850)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (c00000000044ab5c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000456f9c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (c0000000004610c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
```
In mm/memfd.c (c000000000471530)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c00000000054c6c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (c000000000568004)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c0000000006483c0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c00000000076f050)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffe00013c9d6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffe0001d443a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffe0001e2cd2)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffe0001ea624)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/util.c (ffffffe0001f2cb4)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffe0001ff4ec)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffe000203fca)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe0002078da)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffe00020c368)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffe000211472)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000214f76)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffe00021b118)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffe0002205f6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe00022531c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffe0002322ca)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/ksm.c (ffffffe0002354e6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
```
In mm/slub.c (ffffffe00023bc26)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/memcontrol.c (ffffffe000244e2c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memfd.c (ffffffe0002527c2)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffe0002d2edc)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/page.c (ffffffe0002e31f4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffe0003705ac)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffe00042082e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81142ea2)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81212e46)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121fefb)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8122a151)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8122beb5)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8123315d)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81237bfe)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123daca)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff8124a9d4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81250e2e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125268c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81258007)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125f783)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8126681e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8126a1e9)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b62a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81275251)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127cfa1)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f552)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81282249)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128dbde)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81290bed)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81299a55)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812a0ea8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a6f57)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b12be)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b6a25)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812be43b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812c44be)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff812cf5f6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81367ca0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8137a3da)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81419094)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d921a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81136202)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81205bb6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff812130ab)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121d271)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8121ef95)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff812261f7)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122ac3e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff81230aca)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff8123d974)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81243d6e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81245419)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124dac3)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff81251ba3)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812591a6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c3d9)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d8ca)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812671ab)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8126ee17)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81271372)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81273d69)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8127f962)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8128286d)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8128b615)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81292988)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff81298993)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a268e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a7bf5)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812af4ff)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812b54fe)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
```
```
In mm/memfd.c (ffffffff812c026e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81358940)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8136aeaa)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81409b14)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c9bca)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d227)
Location: include/linux/page-flags.h:181
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
In kernel/futex.c (ffffffff81140d52)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81210be6)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121dc9b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81227ef1)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81229c55)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81230efd)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123599e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8123b86a)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff81248774)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124ebce)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125042c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255da7)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125d523)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812645be)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267f89)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812693ca)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81272ff1)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127ad41)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d2f2)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81280059)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128b9ee)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8128e9fd)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81297865)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8129ecb8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a4d67)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812af0ce)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b4835)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812bc24b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812c22ce)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff812cd406)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81365770)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81377eaa)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81415234)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d52aa)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7ff7)
Location: include/linux/page-flags.h:181
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
In kernel/futex.c (ffffffff8114dfa8)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121faf9)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8122cd0b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81237231)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81239050)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81240343)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81245c58)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124af7a)
Location: include/linux/page-flags.h:181
Inline: True
```
```
In mm/compaction.c (ffffffff81257f99)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8125e54e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125fdb0)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81265835)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8126cf07)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81273f7c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81277909)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81278ef5)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81282b53)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8128a91a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128ceba)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128fd49)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8129b7e4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8129e8fd)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a7641)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812aedc4)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812b58c3)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bf41e)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c5208)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cca1c)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812d2d59)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/memfd.c (ffffffff812de186)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81378e50)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8138b95a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8142bf9b)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814ede5a)
Location: include/linux/page-flags.h:181
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2297)
Location: include/linux/page-flags.h:181
Inline: True
```
</details>
</li>
</ul>

## Differences
