# Function: <code>page_ref_inc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100411f)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/gup.c (ffffffff81071601)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/relay.c (ffffffff81144c0b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81189f60)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81199dd4)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a0e40)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811afd49)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811b3e1b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff811b8f30)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811c3526)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811d58c3)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db437)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811df2b0)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811e0282)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff811eecb1)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff811f03a7)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811f241b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fdf76)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811fef7a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204c1d)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81fb6fbc)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81213366)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81217c90)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8121ad3a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8121e011)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8122b625)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8123b896)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8126ba30)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/direct-io.c (ffffffff812750a2)
Location: include/linux/page_ref.h:104
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
```
```
In fs/aio.c (ffffffff81285140)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/dax.c (ffffffff81287a83)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/ext4/inode.c (ffffffff812c8ad9)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff812fdc87)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81318a2b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81342ed8)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134b835)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813805e7)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81442998)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1c5d)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513e9d)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8156a36d)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff815705a9)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8161aefb)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/virtio_net.c (ffffffff816529ae)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165c1d7)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff816fca65)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8176f00e)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff817c8ad3)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6b26)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832dd4)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878fc9)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff81004019)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/gup.c (ffffffff81075172)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/relay.c (ffffffff8114ea8b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81199351)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811a9531)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b0a40)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811c0409)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811c44ab)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff811c9570)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811d3599)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811e58c3)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eafa4)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811ef0c4)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811f01d2)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff811ff5e1)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81200d57)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81202e16)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120ea58)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812107b8)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216d07)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff81ff39d1)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812256ce)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122a24e)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8122c52b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812305eb)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8123db89)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8124e636)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8127eb70)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812889cf)
Location: include/linux/page_ref.h:104
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
```
```
In fs/aio.c (ffffffff81299350)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/dax.c (ffffffff8129c671)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap.c (ffffffff812b0bae)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff812de6bc)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81313d07)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8132ea1f)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81358cf4)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81361145)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff81397068)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81460077)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3c4d)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815402cd)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81596aac)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8159cc69)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8164bb75)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/xen-netfront.c (ffffffff81689fec)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8172e635)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8179c4fe)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff817f86be)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806aca)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81864868)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad6e4)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff81003ddf)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81151155)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811a1398)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811b0a4f)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b7f58)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811c85c2)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811cc8f6)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff811d204b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811dbd2f)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811eeda5)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f6089)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811fa009)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811fadc1)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8120a3f8)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120deb9)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8121a400)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121c0f1)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812226ec)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff820d618d)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81230d80)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81235e4c)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff81238dca)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8123bdc2)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81248b31)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8125a4cb)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8128ca5d)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81295d53)
Location: include/linux/page_ref.h:104
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
```
```
In fs/aio.c (ffffffff812a7041)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff812bdfbf)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8130280c)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8130a8ca)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81343c03)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8136d24a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8137576a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813ad422)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81468b2f)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef9a6)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8155412a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff815aa72c)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff815b0d3a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8165ff34)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/xen-netfront.c (ffffffff8169d911)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff817475a6)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff817bd44a)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81818c65)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81827094)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8188808d)
Location: include/linux/page_ref.h:104
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d2c6b)
Location: include/linux/page_ref.h:104
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff8100402f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8115d955)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811b4f18)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811c45c0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811cc618)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811dd3ee)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811e1916)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff811e74eb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811f1b47)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812052a5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120dcf1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812124a2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812132d5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81223665)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8122912a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8123553e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/ksm.c (ffffffff8123da69)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff826dedd8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124c2ea)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81255c27)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812574c8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125beb6)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81268d1f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8127c7cb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812aefb0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812b8eea)
Location: include/linux/page_ref.h:105
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
```
```
In fs/aio.c (ffffffff812cacda)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff812e18c9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8132719c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8132f3aa)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81368256)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8139207e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8139a8fa)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813d34e2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81494ddf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81524526)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7b6a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816110b2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816178da)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff816c9544)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff816ff3a3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81708971)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff817b9836)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8183581d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff81898cd3)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a5293)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a4d1)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81957b9f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff810046ff)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8116c8c5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/bpf/sockmap.c (ffffffff811cf892)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In kernel/events/core.c (ffffffff811d3d6d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811e4ade)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ed3eb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811fe545)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81202ffe)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff81208a8a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81212030)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812261a9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e76d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812332a9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812341ba)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81246460)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8124a43c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81258482)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8126110d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff82709316)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126fe0f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81279abf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8127b5bb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8127f8c9)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8128dca3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812a364b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812d7482)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812e1b71)
Location: include/linux/page_ref.h:105
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
```
```
In fs/aio.c (ffffffff812f3c24)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff8130dfe1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff81356a5a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8135dd7e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81396ae4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff813c10a2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813c9b1a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff81403b72)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff814c5f88)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a286)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f00ad)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8164ab32)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816513da)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff81705f0c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8173eb0c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817476b1)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818019e6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/sock.c (ffffffff81877431)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/core/skbuff.c (ffffffff8187fb9f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_append_datato_frags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/ipv4/ip_output.c (ffffffff818ecd6c)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818facbe)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81961879)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af83d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff8100472f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8117a5e5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811e426d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811f5195)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811fe8b7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812111d5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8121599e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff8121b72a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812261dd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81239919)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124267e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81246a7a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8124796a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8125a886)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125ea7d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126cb52)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812758e8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffffffff828c05bb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812844bc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128e09f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812900b2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81293fe9)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812a35e3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812b879b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812ec992)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812f67a6)
Location: include/linux/page_ref.h:105
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
```
```
In fs/aio.c (ffffffff813092d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff81323726)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8136ecf0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8137631e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813af85f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff813da404)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813e27c7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8141f812)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff814da79b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571b96)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a68d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81668df2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166f5aa)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170adf2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8172844c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8175fdd1)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176b7ab)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8182dbf7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818a0810)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff818d96d0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818e698a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8191a5c8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81928c01)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977767)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff819961d3)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6d92)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff8100499d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81187435)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811fb43d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8120ce8e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81215bb7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81220857)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81225396)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff8122b3c7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81235b9c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8124aa38)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81251477)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81258c7b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81259cdf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81275863)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812797cc)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/hugetlb.c (ffffffff81287f79)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81290d1a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828d9942)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a139b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8a22)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812aaebd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b0156)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812be951)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812d5432)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8130e13d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81316c83)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff8132a892)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134b817)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d774)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8139814f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8139f803)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813d9daf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81406353)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8140e4ad)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8144d45e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81505db2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a2076)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e3de)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8169e762)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816a50ec)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746592)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81763b64)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8179d4f6)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817a95b0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81870247)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818eb254)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff8192b715)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff819362c5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8197c7d8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198bca6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e128d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a02642)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a562a9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff810049fd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81193355)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8120850d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8121a179)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812234b7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122e307)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81233226)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff812349ee)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81239297)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81243ddc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff81258f08)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125fa27)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126714b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8126818f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81284833)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812892ac)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297b79)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812a0a9a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828e1d98)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b00b3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b9fa2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812bc5e4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c1c46)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812d0841)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812e6fa2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8132115d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81329b01)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff8133da32)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81363ae7)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81365a34)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813b0b8f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813b8673)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813f3dde)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81420eb3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814281e7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8146726e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81523d92)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2ef6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816608be)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816c1812)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816c7e1c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a6e2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81787b54)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817c0f96)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cd020)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818a2047)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8191d3b4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff8195da48)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81969296)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819b3178)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c2589)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18659)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a3921a)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d789)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff8100578d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a7eb5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81231081)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81246b05)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8124ca66)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/filemap.c (ffffffff81250b43)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125a155)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126081b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8126204b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81269f78)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8126f56c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812884be)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128fedf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:copy_one_pte
```
```
In mm/mlock.c (ffffffff81296b03)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8129858f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff812b69de)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812bbc8b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c9c73)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812d5431)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff812e15f6)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812e391d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eeb7f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f19a9)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812f6db6)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8130727d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8131e812)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8135ac3c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff813638e5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81376f82)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6de)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813aceb7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813fc750)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81407efd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8143f9de)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8146ff71)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814bacae)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81587371)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d145)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817105ad)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81774ef7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8177c5bc)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a1dd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_vm_fault
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182c802)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8184c4b5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8188cfbc)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81896dcf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/md/md-bitmap.c (ffffffff81972dd7)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/core/skbuff.c (ffffffff819efafe)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81a2c9ea)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3c6e1)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9d167)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aadbf8)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0938a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e945)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87d7a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mptcp/protocol.c (ffffffff81baab28)
Location: include/linux/page_ref.h:114
Inline: True
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
In arch/x86/entry/vdso/vma.c (ffffffff810046ed)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a54d5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8123ac91)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81251168)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81256ea6)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/filemap.c (ffffffff81259d10)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812642c3)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126a635)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8126c352)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812749cf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8127a8dc)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812921a7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129a95f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a1973)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812a373f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff812c2c2e)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c773b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d58b3)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e0eae)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff812ec546)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812eed8d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa1df)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fdf2d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130228a)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130e9cf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81312fbd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff81329d72)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff81368a7c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff8136fef5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff81384b8c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc53)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff813be59a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8140ee51)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8141a94d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8145baae)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8148a7c2)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814d83ee)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff815a4b48)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d865)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d18d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8178fc47)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8179570c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183d852)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8185c8f5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8189b1f5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff818a6bbf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/md/md-bitmap.c (ffffffff81977cfe)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ef7a7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81a2df9a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3edb1)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa7027)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab4fe6)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17ba5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d395)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9785a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mptcp/protocol.c (ffffffff81bbfe13)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff810046ed)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a60a5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8123f461)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81255268)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8125b336)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/filemap.c (ffffffff8125df50)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81269ea3)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126f76b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff81279cdf)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8127fa16)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81297b02)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/memory.c (ffffffff8129fe4a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a7133)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812a8f7f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/memory_hotplug.c (ffffffff812c6de6)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/madvise.c (ffffffff812c9aaa)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ce0b4)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc5eb)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e85ae)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f4f1d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81300f9b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813048da)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130973e)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/memory-failure.c (ffffffff81314eb7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
```
```
In mm/zsmalloc.c (ffffffff81319206)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8132fd32)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8136ff39)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff81376799)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff8138b679)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d68)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff813c55cd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff814151d1)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81420dfe)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff814613ee)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff81490291)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814ded4e)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff815ae218)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670555)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710efd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff817727b7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817783bc)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818209e2)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8183f7e5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8187da52)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8188a33c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff8195b80a)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d7f62)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81a14c66)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4d12f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a921a7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa018f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05774)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a819)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b86859)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba52e2)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81bafc61)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d1d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811cf835)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81279fd1)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81290caa)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8129713a)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/filemap.c (ffffffff8129a670)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6b33)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff812ac8bb)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff812b7c9f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812bdd47)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812d8542)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/memory.c (ffffffff812e3139)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e8630)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812ea5ef)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8130eaca)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81313534)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8132379b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813304de)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133f51d)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134ac0b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134e63e)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135312e)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In mm/memory-failure.c (ffffffff81360f26)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff813658c5)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/bootmem_info.c (ffffffff8136cb16)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/pipe.c (ffffffff8137d4f2)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff813bea9c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff813c2db3)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff813d8c2c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81413008)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8141536e)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8146874a)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81474abe)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff814b68de)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff814e7d26)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff81537b7e)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81615d64)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4825)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d9fd)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81790ee1)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817f7fe7)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817fde5c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab607)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff818cc874)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8190f151)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191cd51)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81a01003)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a87db2)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81ac860f)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b05849)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4d5b6)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5bf5c)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82c6)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81bf091a)
Location: include/linux/page_ref.h:114
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52c19)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c72e6b)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81c7d707)
Location: include/linux/page_ref.h:114
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff81003dc3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107def7)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81203ac4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812d069a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812e5fac)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff812ecfab)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/filemap.c (ffffffff812f3994)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812fdba9)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff81301564)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81306c02)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff8131382e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813180a7)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81338436)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff81344476)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff8134c461)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff8134d0cc)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81376ab3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137ea0e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8139131c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f2150e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a1056)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b2a8a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b6791)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1da4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c51ac)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813ce5eb)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/memory-failure.c (ffffffff813dc996)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff813e1dae)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/bootmem_info.c (ffffffff813eae96)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/pipe.c (ffffffff813fe2be)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff81445456)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff8144a2b5)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814646f6)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff814883fe)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8148ca45)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff814e833d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff814f6b04)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81540372)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff81576259)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff815cf01d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff816e2979)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:pipe_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f147)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61b6)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff818c952f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff819365fb)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8193de78)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5d56)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81a19c5d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81a62969)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81a72acc)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81b68751)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfd1e0)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81c44b5d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8aeb3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdad98)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ceb15d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db65)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81d88ff0)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df6856)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17cb1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e22bbe)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In arch/x86/entry/vdso/vma.c (ffffffff81004893)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f3df)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8124bbd4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8133a247)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8134fbee)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8135732b)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/filemap.c (ffffffff8135dced)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/page-writeback.c (ffffffff81368384)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff8136bc0f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81371007)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff81386b4a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff8138ab41)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813af2ee)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff813bc5d6)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813c4ff1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813c5d69)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff813f44af)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd3ba)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8140e33c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb48d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814214d2)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff814343a0)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8143813e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f85)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81449515)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453bd5)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/memory-failure.c (ffffffff81463bcd)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff81469391)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/bootmem_info.c (ffffffff83ec85a9)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/pipe.c (ffffffff81487f1e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff814d4cde)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff814d89a1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814f1802)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151cda5)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8151ff55)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff815810bd)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff815910d4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff815deef2)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8161b360)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff8167cb8a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff817d2c8d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193de57)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ae6)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a1a3d5)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a9643b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81a9f2d8)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7331a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81b9ad4d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81bee979)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c0524c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81d041f1)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/core/skbuff.c (ffffffff81dac154)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
```
```
In net/core/filter.c (ffffffff81dff11d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e46013)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9b5be)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eaeee8)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27815)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81f56e1e)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae15)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee51)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ffb8eb)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In arch/x86/entry/vdso/vma.c (ffffffff81004053)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810922df)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81262e44)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8136b12a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81380dad)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81388ba6)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/filemap.c (ffffffff8138fbcb)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/readahead.c (ffffffff8139de9c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a31a4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813b7003)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813bd07d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e3823)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff813f0f8a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
```
```
In mm/mlock.c (ffffffff813f9479)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813fa1b9)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81427b4b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81430697)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8144175c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f71f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814562c8)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81469cf6)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146de0e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81479506)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147f706)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814899d2)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/memory-failure.c (ffffffff81499729)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff8149e320)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/bootmem_info.c (ffffffff836ed619)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/pipe.c (ffffffff814bcdfe)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff81509f47)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/aio.c (ffffffff81529692)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff81554f57)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/mballoc.c (ffffffff815c21a1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8161811e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff816534d0)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e5d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81813693)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982237)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb76)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a637f3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c4b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81aeac38)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc66a8)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81bf120d)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81c46ea9)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c52626)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a95c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf81)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1bfbc)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
```
```
In net/core/filter.c (ffffffff81e70bed)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea16ef)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efa183)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0d02f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f254a7)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f869a4)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb687a)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c097)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ade3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82077c71)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In arch/x86/entry/vdso/vma.c (ffffffff8100695f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810996ff)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8127d064)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81393d6a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813aa16e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff813b2606)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In mm/filemap.c (ffffffff813b9520)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/readahead.c (ffffffff813c7b46)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cce14)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813dfea3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813e7eed)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140e138)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff8141bca5)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff81425019)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81425f79)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8146135b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81469032)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147ba34)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff822325ea)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81490d52)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81498c86)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d3c3)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8a85)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814adbdb)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814b8df1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c8e9b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff814cd452)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/userfaultfd.c (ffffffff814d2c56)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/bootmem_info.c (ffffffff83920619)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/pipe.c (ffffffff814ef2ae)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8153ed76)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/aio.c (ffffffff8155e561)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8158b61e)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In fs/ext4/mballoc.c (ffffffff815facdd)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81651055)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8168cae0)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff816f19bd)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8185923a)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9a47)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2386)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81ab6042)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b3503b)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81b3e118)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b1c8)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81c46acd)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81cfc7c9)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d08801)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_alloc
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f33c)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81e241a8)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed96bc)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__skb_zcopy_downgrade_managed
```
```
In net/core/filter.c (ffffffff81f302c4)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f63eef)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbe0b1)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd112f)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d68)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dfe3)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82084168)
Location: include/linux/page_ref.h:156
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb47)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e765)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8214cdb5)
Location: include/linux/page_ref.h:156
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In virt/kvm/kvm_main.c (ffff8000100b7750)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_fault
```
```
In virt/kvm/arm/mmu.c (ffff8000100cafa4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_pud
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In kernel/relay.c (ffff80001020b84c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffff8000102951cc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffff8000102a5580)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b0dd0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bd1f0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c3404)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffff8000102c50d0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102ca114)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d60f0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffff8000102f211c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa178)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffff8000102fe384)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffff8000102ffda0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffff80001031ecf8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff800010326104)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010335e80)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffff8000103402e4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffff80001034e088)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff8000103530bc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010354b84)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035d578)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363cf0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffff800010375c4c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffff80001038fd40)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffff8000103d9484)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffff8000103e4ee0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffff8000103fcfa0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffff80001042a5a4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c8c0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffff80001048544c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffff80001048f8d0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffff8000104cf3e0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffff800010503b98)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffff80001050c094)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffff8000105569c0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffff80001062dea4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c278)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b008)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffff8000108b2ab0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c900)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffff80001098f0cc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffff8000109dba58)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffff800010a075c4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010af6fcc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffff800010bb7d8c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffff800010bfdb10)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0eca4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffff800010c62b54)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c7519c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e4c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffff800010cf91b4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d59274)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/relay.c (c0449cb8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (c04c2d38)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (c04d4994)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04dd770)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (c04e9750)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c04ee128)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/vmscan.c (c04f3fdc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c04fe3dc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (c0514a78)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c051a584)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:insert_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c051d36c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c051e1d8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/swapfile.c (c053d94c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/ksm.c (c0546988)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c0551b50)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/zsmalloc.c (c0561f1c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (c05766bc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (c05b21ac)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (c05bce50)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (c05cf7f8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c05f2fa4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (c05f54d0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (c0646fe0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (c0650108)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (c06920b0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (c06c020c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c06c79d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (c070b14c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (c07d4f0c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce8d4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c09474fc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (c09af14c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (c0a41e70)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (c0a60a08)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (c0ac5760)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/md/md-bitmap.c (c0bd78f4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In sound/core/pcm_native.c (c0c9146c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data_fault
```
```
In net/core/skbuff.c (c0cd496c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (c0d19dbc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d27220)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c0d734fc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d83848)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c0dddd30)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (c0e00980)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5ac94)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/powerpc/kernel/vdso.c (c000000001348544)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/powerpc/kernel/vdso.c:vdso_init
  - arch/powerpc/kernel/vdso.c:vdso_init
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6368)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
```
```
In kernel/relay.c (c000000000288224)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (c0000000003402e0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (c0000000003582b0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c0000000003662c0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (c000000000375d84)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c00000000037d7d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (c00000000037f934)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (c00000000038698c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c000000000396274)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (c0000000003b6e60)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bf51c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c0000000003c9b64)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c0000000003cb0ec)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (c0000000003f34b8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c0000000003fc650)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c0000000004105d8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c00000000041d688)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (c000000001385424)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004360bc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000444404)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (c000000000448700)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000044f3ac)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (c00000000046863c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (c000000000487308)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (c0000000004dbb64)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (c0000000004eb288)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (c000000000504e0c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c00000000053b0d0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053df2c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (c0000000005aac24)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (c0000000005b551c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (c00000000060815c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (c000000000648938)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c0000000006528c0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (c0000000006b34a0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (c0000000007d1540)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008adea0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d65d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (c00000000094cd64)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (c0000000009554b4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25090)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (c000000000a503f0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (c000000000a9df9c)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (c000000000be306c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (c000000000c8fb90)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (c000000000ce94d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cfb250)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c000000000d67780)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7c8a0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c000000000df31e4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (c000000000e20da0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (c000000000e94e50)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In kernel/relay.c (ffffffe00016c95c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffe0001c45c4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In mm/filemap.c (ffffffe0001d66d8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001dffc8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffe0001e42b8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e9284)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffe0001f19ec)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffe00020489a)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/memory.c (ffffffe0002084a0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffe00020c820)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffe00020d37e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/swapfile.c (ffffffe000226458)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000231fc8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffe000235180)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f082)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/zsmalloc.c (ffffffe00024e3de)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffe00025f582)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffe0002928e0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffe00029aab8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffe0002aaf30)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c805e)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9cd4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffe00030d762)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffe000313f14)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffe000346ca8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffe0003708d0)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffe00037684e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae124)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffe00045dabe)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9c26)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fc50)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffe00056576e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d717c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffe0005f29dc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffe000626424)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8cda)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffe000747708)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffe00077d238)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078b8a6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffe0007cb55e)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d84a4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c86)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffe000844fe4)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000891574)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff810049fd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8118b975)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81200b2d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812127c9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121bb07)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81226957)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8122b876)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8122d03e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812318e7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123c42c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff81251558)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81258077)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125f79b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812607df)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8127ce83)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128188c)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290159)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8129907a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828cac4c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a8693)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b2582)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812b4bc4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812ba226)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c8e21)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812df582)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8131973d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813220e1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81336012)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8135c0c7)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135e014)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813a916f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813b0c53)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813ec3be)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81419493)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814207c7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145f84e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8151c372)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7046)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8162672e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81687262)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8168d86c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171edd2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8173c244)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81785a66)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81791b30)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81847ec7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818bd3b4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff818fda18)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81909266)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81952fe8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819623f9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7ce9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff819d88aa)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2ce19)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff810030dd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8117ea55)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811f387d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81205559)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120ecf7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81219ac7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8121e966)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8122010e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812249a7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122f42c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff81244448)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124db2e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81251bbb)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81252bff)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8126ed37)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127500b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281e04)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8128ac3a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828c3371)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8129a053)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3905)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812a5c16)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812aa243)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812b9e61)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812d01c2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8130a2fd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81312c81)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81326d02)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd67)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134ecb4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff81399bff)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813a16e3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813dce3e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81409f13)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81411247)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145027e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8150c662)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5e26)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161adae)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81664e52)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166b25c)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f8202)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8171dee4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817653b6)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8180f527)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818772f4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff818b7848)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c3076)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8190cad8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191bee9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974ad9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff8199566a)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819ea009)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff810049bd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81189745)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811fe8fd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81210569)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812198a7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812246f7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81229616)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8122adde)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8122f687)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123a1cc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8124f2f8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255e17)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125d53b)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8125e57f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8127ac23)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127f69c)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128df69)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81296e8a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828dd9cc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a64a3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b0392)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812b29d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812b8036)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c6c31)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812dd392)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8131720d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff8131fbb1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81333ae2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81359b97)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135bae4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813a69cf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813ae4b3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813e973e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81415633)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8141c967)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145b8ee)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81518402)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b75d6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816546fe)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816b55a2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816bbadc)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175dba2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8177c9d4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817b5e16)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c1ea0)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818974f7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8190e3b4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff8194ea48)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8195a296)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819bd7b8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ccbc9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22769)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a4332a)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a989c9)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/entry/vdso/vma.c (ffffffff81004afd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811970b5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8120d97d)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8121f4ac)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81228997)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812339c7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81238a26)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffffffff8123a1de)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8123eab8)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812498b7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8125ec68)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812658a5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126cf1f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8126dfcf)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8128a804)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128f36f)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129dd16)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812a6c5a)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/memory_hotplug.c (ffffffff828e2de3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b67be)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c06d2)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff812c2c11)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c8966)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812d728f)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812ee322)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff813285bd)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813318d1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81345b50)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8136d2a7)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136f234)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813bb1b5)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813c2ac1)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813ff042)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8142c3d3)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81433747)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8147308e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81531c82)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d1046)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f17e)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816d0032)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816d60ac)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779242)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81796804)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817d0286)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817dc160)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818b35d7)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8192f4e4)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
```
```
In net/core/filter.c (ffffffff81970418)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197c4b6)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819c70c8)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d6759)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db45)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a4efca)
Location: include/linux/page_ref.h:105
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5063)
Location: include/linux/page_ref.h:105
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
