# Function: <code>get_zone_device_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_zone_device_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e2e0)
Location: kernel/memremap.c:185
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - kernel/relay.c:relay_buf_fault
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:write_one_page
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:special_mapping_fault
  - mm/madvise.c:madvise_free_pte_range
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swapfile.c:unuse_mm
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_page_migrate
  - fs/pipe.c:generic_pipe_buf_get
  - fs/buffer.c:create_empty_buffers
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/aio.c:aio_migratepage
  - fs/dax.c:dax_fault
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/file.c:fuse_readpages_fill
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/md/bitmap.c:read_page
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
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff8119e2e0-ffffffff8119e306: get_zone_device_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_zone_device_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811add10)
Location: kernel/memremap.c:185
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vdso_fault
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
  - kernel/relay.c:relay_buf_fault
  - kernel/events/core.c:perf_mmap_fault
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/page-writeback.c:write_one_page
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_replace_page
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mmap.c:special_mapping_fault
  - mm/madvise.c:madvise_free_pte_range
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swapfile.c:unuse_mm
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/khugepaged.c:collapse_shmem
  - mm/zsmalloc.c:zs_page_migrate
  - fs/pipe.c:generic_pipe_buf_get
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
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
  - fs/aio.c:aio_migratepage
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:grab_mapping_entry
  - fs/iomap.c:iomap_dio_zero
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/file.c:fuse_readpages_fill
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/agp/generic.c:agp_generic_alloc_page
  - drivers/char/agp/generic.c:agp_generic_alloc_pages
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/md/bitmap.c:read_page
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
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffffffff811add10-ffffffff811add36: get_zone_device_page (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
