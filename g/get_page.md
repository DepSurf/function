# Function: <code>get_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071517)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/futex.c (ffffffff810ffc76)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/relay.c (ffffffff8113c6ad)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811796c8)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811877c6)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8118dd31)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff81199428)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8119d691)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a293e)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811a8d6a)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/gup.c (ffffffff811bafeb)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811be0d8)
Location: include/linux/mm.h:487
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
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/mmap.c (ffffffff811c4381)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/swap_state.c (ffffffff811d2723)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811d4597)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811ddc63)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/ksm.c (ffffffff811e57f1)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff811f0d0d)
Location: include/linux/mm.h:487
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
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811fa843)
Location: include/linux/mm.h:487
Inline: True
```
```
In mm/memory-failure.c (ffffffff8120172b)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In fs/pipe.c (ffffffff81214add)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812438fe)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/direct-io.c (ffffffff8124a00d)
Location: include/linux/mm.h:487
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
```
```
In fs/aio.c (ffffffff8125b691)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/ext4/inode.c (ffffffff8129ac8b)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff812cdfe1)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff812eb16d)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8130eac9)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81316b27)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8134aa97)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff813fb680)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages_alloc
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814736ab)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c37dc)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8151753a)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8151d7db)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff815c28dd)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/virtio_net.c (ffffffff815f2d40)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff815fc266)
Location: include/linux/mm.h:487
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8169b92f)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8170801f)
Location: include/linux/mm.h:487
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
Location: include/linux/mm.h:487
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817692fd)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff817c5cc5)
Location: include/linux/mm.h:487
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818076c4)
Location: include/linux/mm.h:487
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff813fb680-ffffffff813fb6a2: get_page (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff81004111)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/gup.c (ffffffff810715f3)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/relay.c (ffffffff81144bfc)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81189f51)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81199dc6)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a0e32)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811afd3b)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811b3e0c)
Location: include/linux/mm.h:761
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
In mm/vmscan.c (ffffffff811b8f22)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811c3514)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811d58b4)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db429)
Location: include/linux/mm.h:761
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
In mm/mlock.c (ffffffff811df2a1)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811e0274)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff811eeca3)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff811f0399)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811f240d)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fdf67)
Location: include/linux/mm.h:761
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
In mm/mempolicy.c (ffffffff811fef6b)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204c0f)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81213358)
Location: include/linux/mm.h:761
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
In mm/huge_memory.c (ffffffff81218471)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8121ad2c)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8121e003)
Location: include/linux/mm.h:761
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8122b617)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8123b888)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8126ba22)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In fs/direct-io.c (ffffffff81275094)
Location: include/linux/mm.h:761
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
In fs/aio.c (ffffffff81285131)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/dax.c (ffffffff81287a75)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/ext4/inode.c (ffffffff812c8aca)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff812fdc78)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81318a1c)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81342eca)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8134b827)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813805d8)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8144298a)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1c4f)
Location: include/linux/mm.h:761
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513e8f)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8156a35f)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8157059b)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8161aeed)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/virtio_net.c (ffffffff8165299d)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165c1c8)
Location: include/linux/mm.h:761
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff816fca57)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8176f000)
Location: include/linux/mm.h:761
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
In net/ipv4/ip_output.c (ffffffff817c8ac5)
Location: include/linux/mm.h:761
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d6b18)
Location: include/linux/mm.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81832dc6)
Location: include/linux/mm.h:761
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81878fbb)
Location: include/linux/mm.h:761
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
In arch/x86/entry/vdso/vma.c (ffffffff8100400b)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/mm/gup.c (ffffffff81075164)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/relay.c (ffffffff8114ea7c)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81199342)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811a9523)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b0a32)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811c03fb)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811c449c)
Location: include/linux/mm.h:750
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
In mm/vmscan.c (ffffffff811c9562)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811d3587)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811e58b4)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaf79)
Location: include/linux/mm.h:750
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
In mm/mlock.c (ffffffff811ef0b5)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811f01c4)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff811ff5d3)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81200d49)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81202e08)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120ea49)
Location: include/linux/mm.h:750
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
In mm/mempolicy.c (ffffffff812107aa)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216cf9)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812256c0)
Location: include/linux/mm.h:750
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
In mm/huge_memory.c (ffffffff8122aa0e)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff8122c51d)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812305dd)
Location: include/linux/mm.h:750
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8123db7b)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8124e628)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8127eb62)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812889c1)
Location: include/linux/mm.h:750
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
In fs/aio.c (ffffffff81299341)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/dax.c (ffffffff8129c313)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap.c (ffffffff812b0ba0)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff812de6ae)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81313cf8)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8132ea10)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81358ce6)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff81361137)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff81397059)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81460068)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3c3f)
Location: include/linux/mm.h:750
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815402bf)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81596a9e)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8159cc5b)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8164bb67)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/xen-netfront.c (ffffffff81689fdd)
Location: include/linux/mm.h:750
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8172e627)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8179c4f0)
Location: include/linux/mm.h:750
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
In net/ipv4/ip_output.c (ffffffff817f86b0)
Location: include/linux/mm.h:750
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81806abc)
Location: include/linux/mm.h:750
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8186485a)
Location: include/linux/mm.h:750
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818ad6d6)
Location: include/linux/mm.h:750
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
In arch/x86/entry/vdso/vma.c (ffffffff81003dd0)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81151146)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811a1389)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811b0a40)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b7f49)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811c85b3)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811cc8e6)
Location: include/linux/mm.h:798
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
In mm/vmscan.c (ffffffff811d203c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811dbd1c)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff811eed97)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f605f)
Location: include/linux/mm.h:798
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
In mm/mlock.c (ffffffff811f9eeb)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff811fadb2)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8120a3e9)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120deaa)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8121a3f1)
Location: include/linux/mm.h:798
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
In mm/mempolicy.c (ffffffff8121c0e2)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812226dd)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230d70)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81236524)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff81238dbb)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8123bdb3)
Location: include/linux/mm.h:798
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81248b22)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8125a4bc)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff8128ca4e)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81295d44)
Location: include/linux/mm.h:798
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
In fs/aio.c (ffffffff812a702a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff812bdfb0)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813027fd)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8130a8bb)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81343bf4)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8136d23b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8137575b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813ad413)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81468b20)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef997)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8155411a)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff815aa71d)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff815b0d2b)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff8165ff25)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/xen-netfront.c (ffffffff8169d902)
Location: include/linux/mm.h:798
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff81747597)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff817bd43b)
Location: include/linux/mm.h:798
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
In net/ipv4/ip_output.c (ffffffff81818c56)
Location: include/linux/mm.h:798
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8182603d)
Location: include/linux/mm.h:798
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8188807e)
Location: include/linux/mm.h:798
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818d2c55)
Location: include/linux/mm.h:798
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
In arch/x86/entry/vdso/vma.c (ffffffff81004020)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8115d946)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811b4f09)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811c45b1)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811cc609)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811dd3df)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811e1906)
Location: include/linux/mm.h:837
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
In mm/vmscan.c (ffffffff811e74dc)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff811f1b34)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81205297)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120dcc9)
Location: include/linux/mm.h:837
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
In mm/mlock.c (ffffffff8121233b)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812132c6)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81223655)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8122911b)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8123552f)
Location: include/linux/mm.h:837
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
Location: include/linux/mm.h:837
Inline: True
```
```
In mm/ksm.c (ffffffff8123da5a)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124c2db)
Location: include/linux/mm.h:837
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
In mm/huge_memory.c (ffffffff81255c15)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812574b9)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8125bea7)
Location: include/linux/mm.h:837
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81268d10)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff8127c7bc)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812aefa1)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812b8edb)
Location: include/linux/mm.h:837
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
In fs/aio.c (ffffffff812cacc3)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff812e18ba)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8132718d)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8132f39b)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81368247)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8139206f)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff8139a8eb)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff813d34d3)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81494dd0)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81524517)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7b5a)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816110a3)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816178cb)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff816c9535)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff816ff98a)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81708962)
Location: include/linux/mm.h:837
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff817b9827)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8183580d)
Location: include/linux/mm.h:837
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
In net/ipv4/ip_output.c (ffffffff81898cc4)
Location: include/linux/mm.h:837
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a40ba)
Location: include/linux/mm.h:837
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8190a4c2)
Location: include/linux/mm.h:837
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81957b89)
Location: include/linux/mm.h:837
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
In arch/x86/entry/vdso/vma.c (ffffffff810046f0)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8116c8b6)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/bpf/sockmap.c (ffffffff811cf884)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In kernel/events/core.c (ffffffff811d3d5e)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811e4acf)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ed3dc)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/page-writeback.c (ffffffff811fe536)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81202fee)
Location: include/linux/mm.h:917
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
In mm/vmscan.c (ffffffff81208a7b)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81212025)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff8122619a)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e769)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8123329a)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812341ab)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81246450)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8124a42d)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81258473)
Location: include/linux/mm.h:917
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
In mm/ksm.c (ffffffff812610fe)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126fdff)
Location: include/linux/mm.h:917
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
In mm/huge_memory.c (ffffffff81279ab8)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff8127b5ac)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8127f8ba)
Location: include/linux/mm.h:917
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8128dc94)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812a3638)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812d7473)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812e1b62)
Location: include/linux/mm.h:917
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
In fs/aio.c (ffffffff812f3c11)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff8130dfd2)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff81356a4b)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8135dd6f)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81396ad5)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff813c1093)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813c9b0b)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff81403b63)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff814c5f7a)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a277)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f009e)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8164ab23)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816513cb)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/scsi/sg.c (ffffffff81705efd)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8173d036)
Location: include/linux/mm.h:917
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817476a2)
Location: include/linux/mm.h:917
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818019d7)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/sock.c (ffffffff81877422)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/core/skbuff.c (ffffffff8187fb90)
Location: include/linux/mm.h:917
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
In net/ipv4/ip_output.c (ffffffff818ecd5d)
Location: include/linux/mm.h:917
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818f9ddc)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff8196186a)
Location: include/linux/mm.h:917
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819af831)
Location: include/linux/mm.h:917
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
In arch/x86/entry/vdso/vma.c (ffffffff81004720)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8117a5d6)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811e425e)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff811f5185)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811fe8a7)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812111c6)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8121598e)
Location: include/linux/mm.h:968
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
In mm/vmscan.c (ffffffff8121b71b)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812261d2)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff8123990a)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81242671)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81246a6b)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8124795b)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8125a876)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125ea6e)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126cb43)
Location: include/linux/mm.h:968
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
In mm/ksm.c (ffffffff812758d9)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812844ac)
Location: include/linux/mm.h:968
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
In mm/huge_memory.c (ffffffff8128e098)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812900a3)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff81293fda)
Location: include/linux/mm.h:968
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812a35d4)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/pipe.c (ffffffff812b8788)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/buffer.c (ffffffff812ec983)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff812f6797)
Location: include/linux/mm.h:968
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
In fs/aio.c (ffffffff813092c1)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap.c (ffffffff8132371f)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8136ece1)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8137630f)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813af850)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff813da3f5)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/file.c (ffffffff813e27b8)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8141f803)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff814da78d)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571b87)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a67e)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81668de3)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166f59b)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8170ade3)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8172843d)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8175fdc2)
Location: include/linux/mm.h:968
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8176b79c)
Location: include/linux/mm.h:968
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8182dbe8)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818a0801)
Location: include/linux/mm.h:968
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
In net/core/filter.c (ffffffff818d96c1)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818e697e)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8191a5b9)
Location: include/linux/mm.h:968
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81927d08)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977758)
Location: include/linux/mm.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff819961c4)
Location: include/linux/mm.h:968
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e6d86)
Location: include/linux/mm.h:968
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
In arch/x86/entry/vdso/vma.c (ffffffff8100498e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81187426)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811fb42e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8120ce7e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81215ba7)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81220847)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81225386)
Location: include/linux/mm.h:1003
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
In mm/vmscan.c (ffffffff8122b3bc)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81235b91)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8124aa2a)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81251473)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81258c6c)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81259cd0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81275854)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812797bc)
Location: include/linux/mm.h:1003
Inline: True
```
```
In mm/hugetlb.c (ffffffff81287f6a)
Location: include/linux/mm.h:1003
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
In mm/ksm.c (ffffffff81290d0b)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a138c)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8a1b)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812aaeae)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812b0147)
Location: include/linux/mm.h:1003
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812be942)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8130e12e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81316c74)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff8132a883)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134b80c)
Location: include/linux/mm.h:1003
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134d764)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8139813f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8139f7f5)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813d9da0)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81406348)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8140e49e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8144d44f)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81505da4)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a2067)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e3ce)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8169e753)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816a50dc)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81746583)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81763b55)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8179d4e7)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817a95a1)
Location: include/linux/mm.h:1003
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81870238)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818eb245)
Location: include/linux/mm.h:1003
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
In net/core/filter.c (ffffffff8192b706)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff819362b5)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8197c7c9)
Location: include/linux/mm.h:1003
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8198ac8e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e127e)
Location: include/linux/mm.h:1003
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a02633)
Location: include/linux/mm.h:1003
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a5629d)
Location: include/linux/mm.h:1003
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
In arch/x86/entry/vdso/vma.c (ffffffff810049ee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81193346)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812084fe)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8121a16a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812234a7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122e2f7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81233216)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffffffff812349df)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8123928c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff81243dd1)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff81258efa)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125fa23)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126713c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81268180)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81284824)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128929c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297b6a)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffff812a0a8b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b00a4)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (ffffffff812b9f9b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812bc5d5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c1c37)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812d0832)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8132114e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81329af2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff8133da23)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81363adc)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff81365a24)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813b0b7f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813b8665)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813f3dcf)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81420ea8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814281d7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8146725f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81523d84)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2ee7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816608ae)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816c1803)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816c7e0c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8176a6d3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81787b45)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817c0f87)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817cd011)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818a2038)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8191d3a5)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffff8195da39)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81969286)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819b3169)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819c14eb)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1864a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a3920b)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a8d77d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100577e)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a7ea6)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81231072)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81246af6)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8124ca57)
Location: include/linux/mm.h:1130
Inline: True
```
```
In mm/filemap.c (ffffffff81250b33)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125a145)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126080c)
Location: include/linux/mm.h:1130
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
In mm/truncate.c (ffffffff8126203b)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81269f6d)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8126f561)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff812884af)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128fedb)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:copy_one_pte
Direct callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/mlock.c (ffffffff81296af4)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81298580)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff812b69cf)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812bbc7b)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812c9c64)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812d5422)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e390d)
Location: include/linux/mm.h:1130
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
In mm/huge_memory.c (ffffffff812eeb74)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f199a)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812f6da7)
Location: include/linux/mm.h:1130
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8130726a)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8135ac2d)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff813638d6)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81376f73)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6da)
Location: include/linux/mm.h:1130
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813acea7)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813fc741)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81407eee)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8143f9ce)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8146ff66)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814bac9f)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81587362)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d136)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171059e)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81774ee8)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8177c5ac)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/heaps/heap-helpers.c (ffffffff8182a1ce)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_vm_fault
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182c7f3)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8184c4a6)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8188cfad)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81896dc0)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/md/md-bitmap.c (ffffffff81972dc7)
Location: include/linux/mm.h:1130
Inline: True
```
```
In net/core/skbuff.c (ffffffff819efaef)
Location: include/linux/mm.h:1130
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
In net/core/filter.c (ffffffff81a2c9db)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3c6d1)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9d158)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aace80)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0937b)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e936)
Location: include/linux/mm.h:1130
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b87d6f)
Location: include/linux/mm.h:1130
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mptcp/protocol.c (ffffffff81baab19)
Location: include/linux/mm.h:1130
Inline: True
```
**Symbols:**

```
ffffffff8128b920-ffffffff8128b933: get_page (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff810046de)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a54c6)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8123ac82)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81251159)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81256e97)
Location: include/linux/mm.h:1172
Inline: True
```
```
In mm/filemap.c (ffffffff81259d00)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812642b3)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126a626)
Location: include/linux/mm.h:1172
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
In mm/truncate.c (ffffffff8126c342)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812749c0)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8127a8d1)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81292198)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129a95b)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a1964)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812a3730)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff812c2c1f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812c772b)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812d58a4)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e0e9f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812eed7d)
Location: include/linux/mm.h:1172
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
In mm/huge_memory.c (ffffffff812fa1d4)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fdf1e)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130227b)
Location: include/linux/mm.h:1172
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81312faa)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff81368a6d)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff8136fee2)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff81384b7d)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813bcc44)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff813be58a)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8140ee42)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff8141a93e)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8145ba9e)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8148a7b2)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814d83df)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff815a4b39)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:copy_page_to_iter_pipe
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d856)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d17e)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff8178fc38)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817956fc)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183d843)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8185c8e6)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8189b1e6)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff818a6bb0)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_release_tx_bufs
```
```
In drivers/md/md-bitmap.c (ffffffff81977cef)
Location: include/linux/mm.h:1172
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ef798)
Location: include/linux/mm.h:1172
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
In net/core/filter.c (ffffffff81a2df8b)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3eda1)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa7018)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab5408)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b96)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d386)
Location: include/linux/mm.h:1172
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b9784f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/mptcp/protocol.c (ffffffff81bbfe04)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810046de)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811a6096)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8123f452)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81255259)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8125b327)
Location: include/linux/mm.h:1202
Inline: True
```
```
In mm/filemap.c (ffffffff8125df40)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81269e93)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126f75c)
Location: include/linux/mm.h:1202
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
In mm/vmscan.c (ffffffff81279cd0)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8127fa0b)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff8129fe3b)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff812a7124)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812a8f70)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff812c9a9b)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff812ce0a4)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff812dc5dc)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e859f)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f4f0d)
Location: include/linux/mm.h:1202
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
In mm/huge_memory.c (ffffffff81300f90)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813048cb)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8130972f)
Location: include/linux/mm.h:1202
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813191f3)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8136ff2a)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff81376786)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff8138b66a)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff813c3d59)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff813c55bd)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff814151c2)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81420def)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff814613de)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff81490281)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff814ded3f)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff815ae20a)
Location: include/linux/mm.h:1202
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
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670546)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710eee)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff817727a8)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817783ac)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818209d3)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8183f7d6)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8187da43)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8188a32d)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff8195b7fb)
Location: include/linux/mm.h:1202
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d7f53)
Location: include/linux/mm.h:1202
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
In net/core/filter.c (ffffffff81a14c57)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4d11e)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a92198)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa05fa)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05765)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a80a)
Location: include/linux/mm.h:1202
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81b8684e)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba52d3)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81bafc52)
Location: include/linux/mm.h:1202
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff8129c470-ffffffff8129c483: get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004d0e)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811cf826)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81279fc2)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81290c9b)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8129712b)
Location: include/linux/mm.h:1206
Inline: True
```
```
In mm/filemap.c (ffffffff8129a660)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/filemap.c:end_page_writeback
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6b23)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff812ac8ac)
Location: include/linux/mm.h:1206
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
In mm/vmscan.c (ffffffff812b7c90)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812bdd3c)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff812e3125)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff812e8621)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812ea5e0)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8130eabb)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81313524)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8132378c)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813304cf)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133f50d)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_prepare
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134ac00)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134e62f)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff8135311f)
Location: include/linux/mm.h:1206
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813658b2)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff813bea8d)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff813c2da0)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/aio.c (ffffffff813d8c1d)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81412ff9)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8141535e)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff8146873a)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff81474aaf)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff814b68ce)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff814e7d16)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff81537b6f)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81615d55)
Location: include/linux/mm.h:1206
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
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4816)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d9ee)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81790ed1)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff817f7fd8)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff817fde4c)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab5f8)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff818cc864)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff8190f142)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff8191cd42)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81a00ff4)
Location: include/linux/mm.h:1206
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a87da3)
Location: include/linux/mm.h:1206
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
In net/core/filter.c (ffffffff81ac8600)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b0583a)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4d5a7)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5c41a)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82b5)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81bf090b)
Location: include/linux/mm.h:1206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c52c0e)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c72e5c)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81c7d6f8)
Location: include/linux/mm.h:1206
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff812dd020-ffffffff812dd033: get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003db5)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dee5)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81203ab6)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812d068f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812e5f97)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff812ecf97)
Location: include/linux/mm.h:1172
Inline: True
```
```
In mm/filemap.c (ffffffff812f0b70)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/swap.c (ffffffff81306bf1)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81318093)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff81344465)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff8134c453)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
```
```
In mm/mmap.c (ffffffff8134d0bf)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81376a9f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137e9fa)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8139130d)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f214d7)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a103d)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b4f20)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In mm/migrate_device.c (ffffffff813b677d)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1d90)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c519a)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813ce5dd)
Location: include/linux/mm.h:1172
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813e1d9a)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/direct-io.c (ffffffff8144a2a7)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814646d9)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/direct-io.c (ffffffff8148ca37)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff814e8329)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff814f6af5)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/fuse/dev.c (ffffffff81576243)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff815cf00f)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff816e2971)
Location: include/linux/mm.h:1172
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
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f136)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61a2)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff818c9521)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff819365ec)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8193de6b)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5d42)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81a19c4b)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81a6295e)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81a72bb7)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/skbuff.c (ffffffff81bfd1ce)
Location: include/linux/mm.h:1172
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
In net/core/filter.c (ffffffff81c44b4a)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8aea4)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdad86)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ce9ee7)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db50)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81d88fde)
Location: include/linux/mm.h:1172
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df6841)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17c9c)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e22baf)
Location: include/linux/mm.h:1172
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff8133eac0-ffffffff8133eb01: get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004885)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f3cd)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8124bbc6)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8133a23c)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/watch_queue.c (ffffffff81357317)
Location: include/linux/mm.h:1224
Inline: True
```
```
In mm/swap.c (ffffffff8136e987)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/memory.c (ffffffff813bc5d1)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mlock.c (ffffffff813c4fe3)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
```
```
In mm/mmap.c (ffffffff813c5d5c)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff813f4933)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd3a6)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8140e328)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb479)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814214be)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8143812a)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f70)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81449501)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453bc8)
Location: include/linux/mm.h:1224
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8146937d)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/direct-io.c (ffffffff814d898f)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8151ff47)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff815810a9)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff815910c5)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/fuse/dev.c (ffffffff8161b34e)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In security/selinux/selinuxfs.c (ffffffff8167cb7c)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff817d2c7a)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193de46)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ad2)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a1a3c7)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a9642c)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81a9f2cb)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73306)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81b9ad3b)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81bee96e)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c05337)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/skbuff.c (ffffffff81dac142)
Location: include/linux/mm.h:1224
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
In net/core/filter.c (ffffffff81dff10a)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e46004)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9b5ac)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eadb7b)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27800)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81f56e0c)
Location: include/linux/mm.h:1224
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae00)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee3c)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ffb8d9)
Location: include/linux/mm.h:1224
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff813b61d0-ffffffff813b6211: get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void get_page(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004045)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810922cd)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81262e36)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8136b11f)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/watch_queue.c (ffffffff81388b92)
Location: include/linux/mm.h:1410
Inline: True
```
```
In mm/memory.c (ffffffff813f0f75)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_wp_page
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mmap.c (ffffffff813fa1ac)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/swapfile.c (ffffffff81430683)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81441749)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8214f70b)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814562af)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8146ddfa)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814794f2)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147f6f2)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814899c1)
Location: include/linux/mm.h:1410
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149e30c)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/ext4/mballoc.c (ffffffff815c2193)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/fuse/dev.c (ffffffff816534be)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e4f)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81813680)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982226)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb62)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a637e5)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c3c)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81aeac2b)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc669d)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81bf11fb)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81c46e9e)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c52614)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff81c6aa47)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/skbuff.c (ffffffff81e1bfa9)
Location: include/linux/mm.h:1410
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
In net/core/filter.c (ffffffff81e70bda)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea16e0)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efa171)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f229e5)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86998)
Location: include/linux/mm.h:1410
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6868)
Location: include/linux/mm.h:1410
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c083)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206adcc)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82077c5f)
Location: include/linux/mm.h:1410
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff813ea410-ffffffff813ea451: get_page (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff81006951)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810996ed)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8127d056)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81393d5f)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/watch_queue.c (ffffffff813b25f2)
Location: include/linux/mm.h:1464
Inline: True
```
```
In mm/memory.c (ffffffff8142066f)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mmap.c (ffffffff81425f6c)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/hugetlb.c (ffffffff8147ba21)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff822325d6)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81490d39)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate_device.c (ffffffff8149e7c4)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a248a)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff814adbc6)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814b8ddd)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffff814cd43e)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/ext4/mballoc.c (ffffffff815facd3)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/fuse/dev.c (ffffffff8168cace)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In security/selinux/selinuxfs.c (ffffffff816f19af)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81859227)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9a36)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2372)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81ab6034)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b3502c)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81b3e10b)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b1bd)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81c46abb)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81cfc7be)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d087f6)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_alloc
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f427)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In net/core/skbuff.c (ffffffff81ed96a9)
Location: include/linux/mm.h:1464
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
In net/core/filter.c (ffffffff81f302b1)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f63ee0)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbe09f)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe63d5)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dfd7)
Location: include/linux/mm.h:1464
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82084156)
Location: include/linux/mm.h:1464
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb33)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e80c)
Location: include/linux/mm.h:1464
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8214cda3)
Location: include/linux/mm.h:1464
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
In virt/kvm/kvm_main.c (ffff8000100b7740)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_fault
```
```
In virt/kvm/arm/mmu.c (ffff8000100caf94)
Location: include/linux/mm.h:1016
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
In kernel/relay.c (ffff80001020b83c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffff8000102951b8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffff8000102a5570)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b0dc0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bd1e0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c33f4)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffff8000102c50c0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102ca104)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d60e0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffff8000102f1a54)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa178)
Location: include/linux/mm.h:1016
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
In mm/mlock.c (ffff8000102fe374)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffff8000102ffd90)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffff80001031ece8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffff8000103260f4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffff800010335e70)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffff8000103402d4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff8000103530ac)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010359f18)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035d568)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363cdc)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffff800010375c3c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffff8000103d9474)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffff8000103e4ed0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffff8000103fcf90)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffff80001042a594)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffff80001042c8b0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffff80001048543c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffff80001048f8c0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffff8000104cf3d0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffff800010503b8c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffff80001050c084)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffff8000105569b0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffff80001062de94)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c268)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082aff4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffff8000108b2aa0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c8f0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffff80001098f0bc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffff8000109dba48)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/net/xen-netfront.c (ffff800010a075b4)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010af6fbc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffff800010bb7d7c)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffff800010bfdb00)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0ec94)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffff800010c62b44)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffff800010c74310)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e3c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffff800010cf91a4)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d59268)
Location: include/linux/mm.h:1016
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
In kernel/relay.c (c0449ca8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (c04c2d2c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (c04d498c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04dd760)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (c04e9748)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c04ee128)
Location: include/linux/mm.h:1016
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
Location: include/linux/mm.h:1016
Inline: False
```
```
In mm/vmscan.c (c04f3fd4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c04fe3d4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1016
Inline: False
```
```
In mm/memory.c (c051a57c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:insert_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c051d364)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c051e1c8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:1016
Inline: False
```
```
In mm/swapfile.c (c053d944)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/ksm.c (c0546978)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c0551b40)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/zsmalloc.c (c0561f14)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (c05b219c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/direct-io.c (c05bce3c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (c05cf7f0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c05f2f98)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (c05f54c0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (c0646fd8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (c0650100)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (c06920a8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (c06c0200)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c06c79c4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (c070b13c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (c07d4f00)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce8c4)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c09474f4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (c09af144)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (c0a41e64)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (c0a609f8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (c0ac5754)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/md/md-bitmap.c (c0bd78e4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In sound/core/pcm_native.c (c0c9145c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_mmap_data_fault
```
```
In net/core/skbuff.c (c0cd4974)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (c0d19db0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d2721c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c0d734f0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d82b70)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c0dddd28)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (c0e00974)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/packet/af_packet.c (c0e5ac90)
Location: include/linux/mm.h:1016
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
In arch/powerpc/kernel/vdso.c (c000000001348530)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/powerpc/kernel/vdso.c:vdso_init
  - arch/powerpc/kernel/vdso.c:vdso_init
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6358)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
```
```
In kernel/relay.c (c000000000288214)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (c0000000003402d4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (c0000000003582a0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c0000000003662a4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (c000000000375d74)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c00000000037d7c4)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (c00000000037f924)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (c00000000038697c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (c00000000039626c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (c0000000003b6e6c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bf518)
Location: include/linux/mm.h:1016
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
In mm/mlock.c (c0000000003c9b54)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (c0000000003cb0dc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (c0000000003f34a8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c0000000003fc640)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c0000000004105c8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c00000000041d678)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c0000000004360ac)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (c0000000004443e4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (c0000000004486f4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (c00000000044f39c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (c00000000046862c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (c0000000004dbb54)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (c0000000004eb278)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (c000000000504dfc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (c00000000053b0c8)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (c00000000053df20)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (c0000000005aac14)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (c0000000005b5510)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (c00000000060814c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (c00000000064892c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (c0000000006528b0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (c0000000006b3490)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (c0000000007d1534)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ade90)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d65b8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (c00000000094cd58)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (c0000000009554a4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25084)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (c000000000a503e0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (c000000000a9df90)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (c000000000be3040)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (c000000000c8fb94)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (c000000000ce94c8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cfb248)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (c000000000d67774)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d7b430)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (c000000000df31d4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (c000000000e20d94)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (c000000000e94e34)
Location: include/linux/mm.h:1016
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
In kernel/relay.c (ffffffe00016c952)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffe0001c45bc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In mm/filemap.c (ffffffe0001d66ca)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001dffbe)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffe0001e4294)
Location: include/linux/mm.h:1016
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
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e9278)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffe0001f19e0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/memory.c (ffffffe000208496)
Location: include/linux/mm.h:1016
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
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffe00020d374)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (0)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/swapfile.c (ffffffe00022644a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffe000231fbe)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffe000235172)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023f076)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/zsmalloc.c (ffffffe00024e3d0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffe0002928d6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffe00029aaaa)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffe0002aaf24)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8050)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffe0002c9cc8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffe00030d754)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffe000313f0c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffe000346c9a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffe0003708c2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffe000376842)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae11a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffe00045dab6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9c1c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fc42)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffe000565764)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d7174)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffe0005f29d2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffe00062641c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8ccc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffe000747708)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffe00077d22e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078b8a6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffe0007cb554)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d784e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c72)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffe000844fda)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffe000891568)
Location: include/linux/mm.h:1016
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
In arch/x86/entry/vdso/vma.c (ffffffff810049ee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8118b966)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81200b1e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812127ba)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121baf7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81226947)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8122b866)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffffffff8122d02f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812318dc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123c421)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8125154a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81258073)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125f78c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff812607d0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8127ce74)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128187c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129014a)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffff8129906b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a8684)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (ffffffff812b257b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812b4bb5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812ba217)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c8e12)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8131972e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813220d2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81336003)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8135c0bc)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135e004)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813a915f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813b0c45)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813ec3af)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81419488)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff814207b7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145f83f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8151c364)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7037)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8162671e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81687253)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8168d85c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8171edc3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8173c235)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81785a57)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81791b21)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81847eb8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818bd3a5)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffff818fda09)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81909256)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81952fd9)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8196135b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7cda)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff819d889b)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a2ce0d)
Location: include/linux/mm.h:1016
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
In arch/x86/entry/vdso/vma.c (ffffffff810030ce)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff8117ea46)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811f386e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8120554a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120ece7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81219ab7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8121e956)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffffffff812200ff)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8122499c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8122f421)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8124443a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124db22)
Location: include/linux/mm.h:1016
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
In mm/mlock.c (ffffffff81251bac)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff81252bf0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8126ed28)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81274ffc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81281df5)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffff8128ac2b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129a044)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (ffffffff812a38fa)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812a5c07)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812aa234)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812b9e52)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff8130a2ee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff81312c72)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81326cf3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd5c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8134eca4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff81399bef)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813a16d5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813dce2f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81409f08)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81411237)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145026f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8150c654)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5e17)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ad9e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff81664e43)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8166b24c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff816f81f3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8171ded5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817653a7)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8180f518)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff818772e5)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffff818b7839)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c3066)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8190cac9)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8191ae4b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974aca)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff8199565b)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffff819e9ffd)
Location: include/linux/mm.h:1016
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
In arch/x86/entry/vdso/vma.c (ffffffff810049ae)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff81189736)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff811fe8ee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8121055a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81219897)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812246e7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81229606)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffffffff8122adcf)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8122f67c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff8123a1c1)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8124f2ea)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255e13)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125d52c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8125e570)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8127ac14)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127f68c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128df5a)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffff81296e7b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a6494)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (ffffffff812b038b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812b29c5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812b8027)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812c6c22)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff813171fe)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff8131fba2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81333ad3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff81359b8c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8135bad4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813a69bf)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813ae4a5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813e972f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff81415628)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff8141c957)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8145b8df)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff815183f4)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b75c7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816546ee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816b5593)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816bbacc)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8175db93)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff8177c9c5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817b5e07)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817c1e91)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818974e8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8190e3a5)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffff8194ea39)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8195a286)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819bd7a9)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819cbb2b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2275a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a4331b)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81a989bd)
Location: include/linux/mm.h:1016
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
In arch/x86/entry/vdso/vma.c (ffffffff81004aee)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In kernel/relay.c (ffffffff811970a6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8120d96e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8121f49d)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81228987)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812339b7)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81238a16)
Location: include/linux/mm.h:1016
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
In mm/truncate.c (ffffffff8123a1cf)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8123eaad)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffffffff812498ac)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/gup.c (ffffffff8125ec5a)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812658a1)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126cf10)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffffffff8126dfc0)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8128a7f5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8128f35f)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129dd06)
Location: include/linux/mm.h:1016
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
In mm/ksm.c (ffffffff812a6c4b)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b67af)
Location: include/linux/mm.h:1016
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
In mm/huge_memory.c (ffffffff812c06cb)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
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
In mm/khugepaged.c (ffffffff812c2c02)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff812c8957)
Location: include/linux/mm.h:1016
Inline: True
```
```
In mm/zsmalloc.c (ffffffff812d727f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/buffer.c (ffffffff813285ae)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In fs/direct-io.c (ffffffff813318c2)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff81345b41)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff8136d29c)
Location: include/linux/mm.h:1016
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8136f224)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff813bb1a6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff813c2ab3)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff813ff033)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8142c3c8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In fs/fuse/file.c (ffffffff81433737)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In security/selinux/selinuxfs.c (ffffffff8147307f)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81531c74)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d1037)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f16e)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/char/virtio_console.c (ffffffff816d0023)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff816d609c)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81779233)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff817967f5)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff817d0277)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817dc151)
Location: include/linux/mm.h:1016
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818b35c8)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
```
In net/core/skbuff.c (ffffffff8192f4d5)
Location: include/linux/mm.h:1016
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
In net/core/filter.c (ffffffff81970409)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197c4a6)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819c70b9)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819d56bb)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db35)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv6/ip6_output.c (ffffffff81a4efbb)
Location: include/linux/mm.h:1016
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa5057)
Location: include/linux/mm.h:1016
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
