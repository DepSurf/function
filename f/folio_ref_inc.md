# Function: <code>folio_ref_inc</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003dc3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107def7)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81203ac4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff812d069a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff812e5fac)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff812ecfab)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/filemap.c (ffffffff812f3994)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff81301564)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81306c02)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813180a7)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/gup.c (ffffffff81338436)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff81344476)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff8134d0cc)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81376ab3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8137ea0e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8139131c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f2150e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff813a1056)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff813b2a8a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b6791)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1da4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c51ac)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffffffff813ce5eb)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813e1dae)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff81445456)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff8144a2b5)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814646f6)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/aio.c:aio_migratepage
```
```
In fs/iomap/buffered-io.c (ffffffff814883fe)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8148ca45)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff814e833d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff814f6b04)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81540372)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff81576259)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff815cf01d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff816e2979)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c61b6)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff818c952f)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff819365fb)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff8193de78)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5d56)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81a19c5d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81a62969)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81a72acc)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81b68751)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bfd1e0)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8aeb3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdad98)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ce9efc)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db65)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81d88ff0)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df6856)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e17cb1)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81e22bbe)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f3df)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8124bbd4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8133a247)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff8134fbee)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff8135732b)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/filemap.c (ffffffff8135dced)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/page-writeback.c (ffffffff81368384)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/readahead.c (ffffffff8136bc0f)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81371007)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff8138ab41)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813af2ee)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff813bc5d6)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813c5d69)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff813f44af)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd3ba)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8140e33c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb48d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814214d2)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff814343a0)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8143813e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f85)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81449515)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453bd5)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81469391)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff814d4cde)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/direct-io.c (ffffffff814d89a1)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/aio.c (ffffffff814f1802)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8151cda5)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/iomap/direct-io.c (ffffffff8151ff55)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/ext4/inode.c (ffffffff815810bd)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
```
In fs/ext4/mballoc.c (ffffffff815910d4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff815deef2)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:release_buffer_page
```
```
In fs/fuse/dev.c (ffffffff8161b360)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff8167cb8a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff817d2c8d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:pipe_get_pages
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193de57)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16ae6)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a1a3d5)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81a9643b)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81a9f2d8)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7331a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81b9ad4d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81bee979)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/xen-netfront.c (ffffffff81c0524c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81d041f1)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/core/skbuff.c (ffffffff81dac154)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e46013)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9b5be)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eadb92)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27815)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/ipv6/ip6_output.c (ffffffff81f56e1e)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fcae15)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81feee51)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff81ffb8eb)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810922df)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff81262e44)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff8136b12a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff81380dad)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff81388ba6)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/filemap.c (ffffffff8138fbcb)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/readahead.c (ffffffff8139de9c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813a31a4)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813bd07d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e3823)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/gup.c:migrate_longterm_unpinnable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff813f0f8a)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff813fa1b9)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff81427b4b)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81430697)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8144175c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f71f)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff814562c8)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81469cf6)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146de0e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81479506)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147f706)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814899d2)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149e320)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff81509f47)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/aio.c (ffffffff81529692)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff81554f57)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/mballoc.c (ffffffff815c21a1)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff8161811e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff816534d0)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff816b4e5d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff81813693)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982237)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fb76)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81a637f3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81ae1c4b)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81aeac38)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc66a8)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81bf120d)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81c46ea9)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c52626)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a95c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cf81)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1bfbc)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea16ef)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efa183)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f229f4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f869a4)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81fb687a)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202c097)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8206ade3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff82077c71)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810996ff)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In kernel/relay.c (ffffffff8127d064)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/events/core.c (ffffffff81393d6a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap_fault
```
```
In kernel/events/uprobes.c (ffffffff813aa16e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/watch_queue.c (ffffffff813b2606)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In mm/filemap.c (ffffffff813b9520)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:splice_folio_into_pipe
  - mm/filemap.c:folio_end_writeback
  - mm/filemap.c:replace_page_cache_folio
```
```
In mm/readahead.c (ffffffff813c7b46)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff813cce14)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:folio_isolate_lru
```
```
In mm/shmem.c (ffffffff813e7eed)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140e138)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
```
```
In mm/memory.c (ffffffff8141bca5)
Location: include/linux/page_ref.h:163
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
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
```
```
In mm/mmap.c (ffffffff81425f79)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
```
```
In mm/madvise.c (ffffffff8146135b)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81469032)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147ba34)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff822325ea)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81490d52)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81498c86)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d3c3)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8a85)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814adbdb)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:set_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814b8df1)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffff814cd452)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In mm/userfaultfd.c (ffffffff814d2c56)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In fs/buffer.c (ffffffff8153ed76)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In fs/aio.c (ffffffff8155e561)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/aio.c:aio_migrate_folio
```
```
In fs/iomap/buffered-io.c (ffffffff8158b61e)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_alloc
```
```
In fs/ext4/mballoc.c (ffffffff815facdd)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/jbd2/commit.c (ffffffff81651055)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/fuse/dev.c (ffffffff8168cae0)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In security/selinux/selinuxfs.c (ffffffff816f19bd)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In lib/iov_iter.c (ffffffff8185923a)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9a47)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2386)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff81ab6042)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/char/virtio_console.c (ffffffff81b3503b)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/agp/generic.c (ffffffff81b3e118)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b1c8)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/sg.c (ffffffff81c46acd)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffffffff81cfc7c9)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_build_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d08801)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_alloc
  - drivers/net/virtio_net.c:virtnet_rq_alloc
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f33c)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
```
In drivers/md/md-bitmap.c (ffffffff81e241a8)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed96bc)
Location: include/linux/page_ref.h:163
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
In net/core/filter.c (ffffffff81f302c4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f63eef)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fbe0b1)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe63e4)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dfe3)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff82084168)
Location: include/linux/page_ref.h:163
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fbb47)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff8213e765)
Location: include/linux/page_ref.h:163
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_build_skb_zerocopy
```
```
In net/mptcp/protocol.c (ffffffff8214cdb5)
Location: include/linux/page_ref.h:163
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
